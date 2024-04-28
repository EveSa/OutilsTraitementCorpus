FROM alpine:latest

RUN apk update && apk add bash
RUN apk add --update --no-cache openssh\
 sqlite\
 python3\
 py3-pip
RUN apk add gcompat libstdc++ curl

RUN adduser -h /home/user -s /bin/sh -D user
RUN echo "PasswordAuthentication yes" >> /etc/ssh/sshd_config
RUN echo -n "user:defaultpassword" | chpasswd
ENTRYPOINT ["/entrypoint.sh"]
EXPOSE 22
COPY entrypoint.sh /
