FROM minibase:1.0

ADD ./bin/etcd /usr/local/bin/
ADD ./bin/etcdctl /usr/local/bin/
RUN export ETCD_UNSUPPORTED_ARCH=sw64
RUN mkdir -p /var/etcd/
RUN mkdir -p /var/lib/etcd/

EXPOSE 2379 2380

CMD ["/usr/local/bin/etcd"]



















