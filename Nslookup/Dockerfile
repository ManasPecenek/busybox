FROM busybox:1.33.1

WORKDIR /home


RUN wget http://rpmfind.net/linux/centos/8.4.2105/AppStream/x86_64/os/Packages/bind-utils-9.11.26-4.el8_4.x86_64.rpm


RUN rpm -i bind-utils-9.11.26-4.el8_4.x86_64.rpm


RUN rm -rf bind-utils-9.11.26-4.el8_4.x86_64.rpm
