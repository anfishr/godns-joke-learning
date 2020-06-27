# godns + joke  docker learning

> for better we can use coredns

## some notes

* redis keys 

Must add one hash key  first

```code
hset godns:hosts demo.rong.com 192.168.0.109
```

* dig test

```code
dig @127.0.0.1 demo.rong.com
```

* better together with coredns 