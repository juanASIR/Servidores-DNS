## /etc/bind/named.conf.local.

```
zone "jperalb.com" in {
   type master;
   file "db.master.jperalb.com";
   allow-transfer { 192.168.1.3; };
};

zone "1.168.192.IN-ADDR.ARPA" in {
   type master;
   file "db.master.192.168.1.rev";
   allow-transfer { 192.168.1.3; };
};
```
