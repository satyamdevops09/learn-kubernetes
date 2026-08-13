FROM redhat/ubi9
ADD  sample.txt opt/sample.txt
ARG  URL
RUN  echo "URL is $URL"
ENV  URL1=google.com
USER bin
WORKDIR /etc
ENTRYPOINT    ["id"]
# ENTRYPOINT    ["ping", "-c", "3"]
CMD           ["yahoo.com"]