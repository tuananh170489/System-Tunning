# Disable Huge Pages
```
echo never > /sys/kernel/mm/transparent_hugepage/enabled
```
# Storage I/O
```
/sys/block/*/queue/rq_affinity  2
/sys/block/*/queue/scheduler        noop
/sys/block/*/queue/nr_requests  256
/sys/block/*/queue/read_ahead_kb    256
```
