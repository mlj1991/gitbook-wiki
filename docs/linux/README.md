# 机器性能检测工具

## CPU && Memory
```
top
htop
```

## Disk
```
iotop
iostat
```

## Network

实时使用：
```
iftop
```

带宽上限：
```
iperf -s
iperf -c 10.10.30.171 -t 10 -P 10
```

## GPU
```
nvidia-smi
```

## InfiniBand
```
ib_write_bw
ib_write_lat
```
