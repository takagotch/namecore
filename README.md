### namecore
---
https://github.com/domob1812/namecore

```py
// test/functional/.
with node.profile_with_perf("send-big-msgs"):
  for _ in range(100000):
    node.p2p.send_message(some_large_message)
```

```sh
perf report -i /path/to/datadir/send-big/msgs.perf.data.xxxx --stdio | c++filt | less
```

```
```


