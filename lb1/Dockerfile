FROM ubha:v1
ADD keepalived.conf /etc/keepalived/keepalived.conf 
ADD haproxy.cfg /etc/haproxy/haproxy.cfg
ENTRYPOINT service haproxy start && service keepalived start && /bin/bash
CMD ["echo "net.ipv4.ip_nonlocal_bind=1" >> /etc/sysctl.conf"]
