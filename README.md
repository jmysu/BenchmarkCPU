## Benchmark available CPUs
CPU sysbench/bogomips

### Apple iMac Intel Core i5 CPU 750  @ 2.67GHz  (310Watt)
```
sysbench 1.0.15 (using bundled LuaJIT 2.1.0-beta2)

Running the test with following options:
Number of threads: 1
Initializing random number generator from current time
Prime numbers @imit: 10000
Initializing worker threads...
Threads started!
CPU speed:
    events per second:   928.48
```
```
BogoMips V1.3 Portable
Calibrating delay loop.. ok - 3168.00 BogoMips
```

### ASUS EB1033 Intel Atom CPU D2550 @ 1.86GHz (65Watt)
```
sysbench 1.0.11 (using system LuaJIT 2.1.0-beta3)

Running the test with following options:
Number of threads: 1
Initializing random number generator from current time
Prime numbers limit: 10000
Initializing worker threads...
Threads started!
CPU speed:
    events per second:   109.39
```
```
BogoMips V1.3 Portable
Calibrating delay loop.. ok - 1842.00 BogoMips
```

### Raspberry Pi3B+ Broadcom BCM2837 @ 1.4GHz (5V 700mA)
```
sysbench 1.1.0 (using bundled LuaJIT 2.1.0-beta3)

Running the test with following options:
Number of threads: 1
Initializing random number generator from current time
Prime numbers limit: 10000
Initializing worker threads...
Threads started!
CPU speed:
    events per second:    68.89
```
```
pi@rasbian:~ $ cat /proc/cpuinfo
processor	: 0
model name	: ARMv7 Processor rev 4 (v7l)
BogoMIPS	: 38.40
```

### Raspberry Pi Zero W (5V 230mA)
```

```
