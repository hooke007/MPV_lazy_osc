# Preview & Description
![lazy_osc.jpg](https://i.loli.net/2020/05/21/TbWcxfakqJ1wdVz.jpg)

The (old version's) built-in osc UI inside _"MPV_lazy"_ https://github.com/hooke007/MPV_lazy

It is modified from _"mpv_thumbnail_script"_ https://github.com/TheAMM/mpv_thumbnail_script
and official "osc.lua" https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua

## Installation
Just download all files into your mpv'config folder!

Remember to back you original `osc.conf` file.

It is not compatible with other `osc-like` lua files. （e.g. delete the original <s>mpv_thumbnail_script_client_osc.lua</s>）

You should add `osc=no` and `load-scripts=yes` in your `mpv.conf`

```
File Tree
    ...\mpv\portable_config\
        mpv.conf

    ...\mpv\portable_config\scripts\
            osc_mod.lua
            mpv_thumbnail_script_server.lua
            mpv_thumbnail_script_server-1.lua
            mpv_thumbnail_script_server-2.lua (more 'server' will speed up but higher usage of CPU)

    ...\mpv\portable_config\script-opts\
            osc.conf
            mpv_thumbnail_script.conf
```
