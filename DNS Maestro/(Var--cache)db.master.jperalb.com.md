## /var/cache/bind/db.master.jperalb.com

```
$TTL 2d
$ORIGIN jperalb.com.

@         IN    SOA   ns1.jperalb.com. hostmaster.jperalb.com. (
                      2016040800  ; se = serial number
                      12h         ; ref = refresh
                      15m         ; ret = refresh retry
                      3w          ; ex = expiry
                      2h          ; nx = nxdomain ttl
                      )
          IN    NS    ns1
          IN    NS    ns2

ns1       IN    A         192.168.1.2
ns2       IN    A         192.168.1.3
www       IN    A         192.168.1.11
ftp       IN    CNAME     www
```
