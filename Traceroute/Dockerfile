FROM busybox:1.33.1


WORKDIR /home


RUN wget http://rpmfind.net/linux/dag/redhat/el6/en/i386/dag/RPMS/tcptraceroute-1.5-0.beta7.el6.rf.i686.rpm


RUN rpm -i tcptraceroute-1.5-0.beta7.el6.rf.i686.rpm


RUN rm -rf tcptraceroute-1.5-0.beta7.el6.rf.i686.rpm
