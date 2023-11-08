## /etc/bind/named.conf.local

```
zone "jperalb.com" in {
   type slave;
   file "db.slave.jperalb.com";
   masters { 192.168.1.2; };
   allow-notify { 192.168.1.2; };
};

zone "1.168.192.IN-ADDR.ARPA" in {
   type slave;
   file "db.slave.192.168.1.rev";
   masters { 192.168.1.2; };
   allow-notify { 192.168.1.2; };
};
```
