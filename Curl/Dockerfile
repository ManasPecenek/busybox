FROM busybox:1.33.1


WORKDIR /home


RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/libssh2-1.8.0-4.el7.x86_64.rpm 
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/openssl-libs-1.0.2k-19.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/nss-util-3.44.0-4.el7_7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/nss-3.44.0-7.el7_7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/nspr-4.21.0-1.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/cyrus-sasl-lib-2.1.26-23.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/openldap-2.4.44-22.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/libidn-1.28-4.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/keyutils-libs-1.5.8-3.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/pcre-8.32-17.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/libselinux-2.5-15.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/krb5-libs-1.15.1-50.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/libcom_err-1.42.9-19.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/nss-softokn-freebl-3.44.0-8.el7_7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/glibc-2.17-317.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/zlib-1.2.7-18.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/nss-pem-1.0.3-7.el7.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/updates/x86_64/Packages/libcurl-7.29.0-59.el7_9.1.x86_64.rpm
RUN wget http://mirror.centos.org/centos/7/os/x86_64/Packages/curl-7.29.0-59.el7.x86_64.rpm


RUN rpm -i libssh2-1.8.0-4.el7.x86_64.rpm && \
rpm -i openssl-libs-1.0.2k-19.el7.x86_64.rpm && \
rpm -i nss-util-3.44.0-4.el7_7.x86_64.rpm && \
rpm -i nss-3.44.0-7.el7_7.x86_64.rpm && \
rpm -i nspr-4.21.0-1.el7.x86_64.rpm && \
rpm -i cyrus-sasl-lib-2.1.26-23.el7.x86_64.rpm && \
rpm -i openldap-2.4.44-22.el7.x86_64.rpm && \
rpm -i libidn-1.28-4.el7.x86_64.rpm && \
rpm -i keyutils-libs-1.5.8-3.el7.x86_64.rpm && \
rpm -i pcre-8.32-17.el7.x86_64.rpm && \
rpm -i libselinux-2.5-15.el7.x86_64.rpm && \
rpm -i krb5-libs-1.15.1-50.el7.x86_64.rpm && \
rpm -i libcom_err-1.42.9-19.el7.x86_64.rpm && \
rpm -i nss-softokn-freebl-3.44.0-8.el7_7.x86_64.rpm && \
rpm -i glibc-2.17-317.el7.x86_64.rpm && \
rpm -i zlib-1.2.7-18.el7.x86_64.rpm && \
rpm -i nss-pem-1.0.3-7.el7.x86_64.rpm && \
rpm -i libcurl-7.29.0-59.el7_9.1.x86_64.rpm && \
rpm -i curl-7.29.0-59.el7.x86_64.rpm


RUN rm -rf ./*.rpm
