FROM redhat/ubi9
ADD  sample.txt opt/sample.txt
ARG  URL
RUN  echo "URL is $URL"
ENV  URL1=google.com
RUN  dnf install iputils-20210202-15.el9_7.x86_64 -y
USER bin
WORKDIR /etc
# ENTRYPOINT    ["id"]
# ENTRYPOINT    ["ping", "-c", "3"]
# CMD           ["yahoo.com"]