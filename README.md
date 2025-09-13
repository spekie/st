# patches applied
- alpha
# patching
```sh
patch -F3 -i *.diff
```
# config.h changes
```diff
8c8
< static char *font = "Liberation Mono:pixelsize=12:antialias=true:autohint=true";
---
> static char *font = "Liberation Mono:pixelsize=15:antialias=true:autohint=true";
```
