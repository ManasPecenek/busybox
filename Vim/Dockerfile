FROM busybox:1.33.1

WORKDIR /home

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/libattr-2.4.48-3.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/libacl-2.2.53-1.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/glibc-common-2.28-151.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/glibc-all-langpacks-2.28-151.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/glibc-2.28-151.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/AppStream/x86_64/os/Packages/gpm-libs-1.20.7-17.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/pcre2-10.32-2.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/libsepol-2.9-2.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/libselinux-2.9-5.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/ncurses-base-6.1-7.20180224.el8.noarch.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/ncurses-libs-6.1-7.20180224.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/AppStream/x86_64/os/Packages/vim-filesystem-8.0.1763-15.el8.noarch.rpm

RUN wget http://mirror.centos.org/centos/8/AppStream/x86_64/os/Packages/vim-common-8.0.1763-15.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/BaseOS/x86_64/os/Packages/which-2.21-12.el8.x86_64.rpm

RUN wget http://mirror.centos.org/centos/8/AppStream/x86_64/os/Packages/vim-enhanced-8.0.1763-15.el8.x86_64.rpm

RUN rpm -i libattr-2.4.48-3.el8.x86_64.rpm && \
rpm -i libacl-2.2.53-1.el8.x86_64.rpm && \
rpm -i glibc-common-2.28-151.el8.x86_64.rpm && \
rpm -i glibc-all-langpacks-2.28-151.el8.x86_64.rpm && \
rpm -i glibc-2.28-151.el8.x86_64.rpm && \
rpm -i gpm-libs-1.20.7-17.el8.x86_64.rpm && \
rpm -i pcre2-10.32-2.el8.x86_64.rpm && \
rpm -i libsepol-2.9-2.el8.x86_64.rpm && \
rpm -i libselinux-2.9-5.el8.x86_64.rpm && \
rpm -i ncurses-base-6.1-7.20180224.el8.noarch.rpm && \
rpm -i ncurses-libs-6.1-7.20180224.el8.x86_64.rpm && \
rpm -i vim-filesystem-8.0.1763-15.el8.noarch.rpm && \
rpm -i vim-common-8.0.1763-15.el8.x86_64.rpm && \
rpm -i which-2.21-12.el8.x86_64.rpm && \
rpm -i vim-enhanced-8.0.1763-15.el8.x86_64.rpm

RUN rm -rf ./*.rpm
