FROM busybox:1.33.1

WORKDIR /home

RUN wget http://rpmfind.net/linux/centos/8.4.2105/BaseOS/aarch64/os/Packages/curl-7.61.1-18.el8.aarch64.rpm

RUN rpm -i ./*.rpm

# RUN wget http://www.magicermine.com/demos/curl/curl/curl-7.30.0.ermine.tar.bz2


# RUN wget http://rpmfind.net/linux/centos/8.4.2105/AppStream/aarch64/os/Packages/vim-common-8.0.1763-15.el8.aarch64.rpm


# RUN wget http://rpmfind.net/linux/epel/8/Everything/aarch64/Packages/n/netcat-1.217-3.el8.aarch64.rpm


# RUN wget http://rpmfind.net/linux/dag/redhat/el6/en/i386/dag/RPMS/tcptraceroute-1.5-0.beta7.el6.rf.i686.rpm


# RUN wget http://rpmfind.net/linux/centos/8-stream/AppStream/x86_64/os/Packages/mysql-8.0.21-1.module_el8.4.0+589+11e12751.x86_64.rpm


# RUN wget http://rpmfind.net/linux/centos/8.4.2105/AppStream/x86_64/os/Packages/bind-utils-9.11.26-4.el8_4.x86_64.rpm


# RUN rpm -i bind-utils-9.11.26-4.el8_4.x86_64.rpm && \

# tar -xvf curl-7.30.0.ermine.tar.bz2 && \

# mv /home/curl-7.30.0.ermine/curl.ermine /bin/curl && \

# rm -Rf /home/curl-7.30.0.ermine && \

# rpm -i vim-common-8.0.1763-15.el8.aarch64.rpm && \

# rpm -i netcat-1.217-3.el8.aarch64.rpm && \

# rpm -i tcptraceroute-1.5-0.beta7.el6.rf.i686.rpm && \

# rpm -i mysql-8.0.21-1.module_el8.4.0\+589\+11e12751.x86_64.rpm

RUN rm -rf ./*.rpm && rm -rf ./*.bz2
