## Intel as Display, NVIDIA for Cuda

```bash
prime-select on-demand
```

`/etc/X11/xorg.conf`

```bash
Section "Device"
    Identifier      "intel"
    Driver          "intel"
    BusId           "PCI:0:2:0"
    Option          "TearFree"      "true"
    Option          "DRI"           "3"
EndSection

Section "Screen"
    Identifier      "intel"
    Device          "intel"
EndSection
```
