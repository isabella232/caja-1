# caja-1.16

A fork of the [caja](https://github.com/mate-desktop/caja/tree/1.16) file manager (1.16).

## How to build

```
$ ./autogen.sh
$ ./configure \
    --prefix=/usr \
    --libexecdir=/usr/lib/caja \
    --with-gtk=2.0 \
    --enable-introspection \
    --disable-update-mimedb
$ make
$ src/caja
```
