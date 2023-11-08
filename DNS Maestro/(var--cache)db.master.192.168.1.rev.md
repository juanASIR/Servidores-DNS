## /var/cache/bind/db.master.192.168.1.rev

 ```
$TTL 2d
$ORIGIN 1.168.192.IN-ADDR.ARPA.

@         IN    SOA   ns1.jperalb.com. hostmaster.jperalb.com. (
                      2016040800  ; se = serial number
                      12h         ; ref = refresh
                      15m         ; ret = refresh retry
                      3w          ; ex = expiry
                      2h          ; nx = nxdomain ttl
                      )
          IN    NS    ns1.jperalb.com.
          IN    NS    ns2.jperalb.com.

2       IN    PTR         ns1.jperalb.com.
3       IN    PTR         ns2.jperalb.com.
11      IN    PTR         www.jperalb.com.
11      IN    PTR         ftp.jperalb.com.
```
