git clone https://github.com/iincmd/v2ray -b master


cd v2ray

chmod +x install.sh

./install.sh local

某些需安装git后逐行编译

要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统

推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。

备注：不推荐使用 Debian 8 系统，因为 Caddy 申请证书可能会出现一些莫名其妙的问题

https://github.com/233boy/v2ray/fork
