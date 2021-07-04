FROM busybox:1.33.1

WORKDIR /home


RUN wget http://rpmfind.net/linux/epel/8/Everything/aarch64/Packages/n/netcat-1.217-3.el8.aarch64.rpm


RUN rpm -i netcat-1.217-3.el8.aarch64.rpm


RUN rm -rf netcat-1.217-3.el8.aarch64.rpm
