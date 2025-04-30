1.运行 OpenWrt Builder 工作流，Enable SSH connection to Actions  为true

2.等待工作流进行到 SSH 输出链接，点击打开网页SSH

3.ctrl+c（网页终端可能会遇到黑屏的情况，按 Ctrl+C 即可）

cd openwrt

make menuconfig  选择配置，两次esc键返回ssh，执行make defconfig  

完成后按Ctrl+D组合键或执行exit命令退出，后续编译工作将自动进行

致谢

https://github.com/P3TERX/Actions-OpenWrt

https://github.com/coolsnowwolf/lede
