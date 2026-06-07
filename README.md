## Ignores

- [ignores/README.md](./ignores/README.md)

```bashhttps://github.com/theanotherwise/workspace/blob/plasma/README.md
konsole --tabs-from-file konsole.tabs --profile  TheAnotherWise
```

## KDE Plasma Widgets

```bash
qdbus org.kde.plasmashell /PlasmaShell evaluateScript "lockCorona(true)"

qdbus org.kde.plasmashell /PlasmaShell evaluateScript "lockCorona(false)"
```

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

## MacOS

### Override iterm2

<img width="367" height="151" alt="image" src="https://github.com/user-attachments/assets/9b016287-b2e8-474a-a40b-0d03ca412353" />
