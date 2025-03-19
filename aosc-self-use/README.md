# aosc-self-use

这个仓库用于存放自用的 AOSC OS 软件构建脚本。  
如有可能（如果有空），部分软件包将会被推送至主源。

预构建二进制包将会上传至本仓库 release ，不定期更新。

可用的软件包：  
```
libtas xcb-util+32 xcb-util-keysyms+32
```

构建顺序（含依赖）:  
libtas:  
```
xcb-util+32 xcb-util-keysyms+32 libtas
```
