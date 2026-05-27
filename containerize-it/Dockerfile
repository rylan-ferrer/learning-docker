FROM alpine:latest

RUN apk add --no-cache bash figlet

COPY /devops-pipeline.sh /devops-pipeline.sh
RUN chmod u+x /devops-pipeline.sh

CMD ["bash", "/devops-pipeline.sh"]
