GALasm 2.1
===
Portable GAL Assembler

# Introduction

GALasm was created simply because there were no other open source GAL assemblers. The assembler core is basically the one of GALer, a GAL development environment for the Amiga platform. I was unable to get in touch with his author to get the permission to do the port, so if he complains i'll have to stop the development.


# Copyright

GALasm is Copyright (c) 1998-2003 by Alessandro Zummo

Original sources Copyright (c) 1991-96 Christian Habermann, but any bug and any piece of code taken from the original GALer sources is still Copyright (c) 1991-96 by Christian Habermann.

**Commercial use is strictly forbidden!**

In This fork, [funcman](hyq1986@gmail.com) added the xmake build script and changed some C function names to avoid symbol conflicts when linking on MS Windows. And does not hold any copyright.

# Build

You can build GALasm by xmake:
```sh
$ xmake
```

Also you can build by GNU Make:
```sh
$ cd src
$ make
```

# Usage

On shell:
```sh
$ GALasm YOUR_PLD_FILE.pld
```

Than you can get files like this:
```sh
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         2023/2/10     14:49           1280 GAL22V10.chp
-a----         2023/2/10     14:49           8478 GAL22V10.fus
-a----         2023/2/10     14:49            862 GAL22V10.jed
-a----         2023/2/10     14:49            712 GAL22V10.pin
-a----         2023/2/10     14:43            731 GAL22V10.pld
```

# Others

Please read README files and docs in galer folder. These are the original documents.

You can also get the commercial software WinCUPL through this link:

<https://www.microchip.com/en-us/products/fpgas-and-plds/spld-cplds/pld-design-resources>

But I think open source is the best.