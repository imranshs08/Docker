FROM busybox
RUN mkdir -p  /root/demo/context1/context2
WORKDIR /root/demo
WORKDIR context1
WORKDIR context2
RUN touch file01.txt
CMD ["/bin/sh"]
