📦 OpenWrt Builder

GitHub Actions 自动化编译 OpenWrt 固件，SSH 远程配置，支持发布 Release，一键构建你的专属固件。

📦 使用方法

运行 OpenWrt Builder 工作流，设置 Enable SSH connection to Actions 为 true

等待 Actions 输出 SSH 连接链接，点击打开网页终端

出现黑屏时按 Ctrl+C，输入以下命令：

cd openwrt

make menuconfig

完成配置后，按两次 Esc 退出菜单并保存

输入 exit 或 Ctrl+D 退出 SSH，工作流将继续自动编译


🚀 致谢

coolsnowwolf/lede 

P3TERX/Actions-OpenWrt

🛠️ 如果你觉得这个项目有帮助，欢迎 Star、Fork、分享！
