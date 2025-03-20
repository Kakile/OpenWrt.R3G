<div align="center">
<a href="https://downloads.openwrt.org/" target="_blank">
  <img width="500" src="https://github.com/Kakile/OpenWrt.R3G/blob/73bda9d2e889d799e7085991bbea177cda793f73/Images/OpenWrt.png" alt="OpenWrt logo"/></a>
</div>

# 🗂️OpenWrt.R3G
| OpenWrt | 24.10.0 |
| :------ |:-------:|
Architecture|MIPS
Targets|ramips
Vendor|Mediatek
Bootloader|Breed
System-On-Chip|MT7621 Family
CPU/Speed|mipsel_24kc @ 880MHz 2 core
Flash|128MB SLC Nand Flash
RAM|RAM 256MB DDR3-1200
Wireless|2.4G MT7603EN WiFi 2X2 802.11N<br>5G MT7612EN WiFi 2X2 802.11AC
Ethernet|3x1000Mbit/s VLAN Support
USB|1x3.0 
DC Output|5V/1A

```
[Latest Stable Release](https://firmware-selector.openwrt.org/)
```

## 📔必装插件:
> 仅收录WebUI,对应核心·依赖·翻译包自动补齐
### 通过官方渠道✨

* luci-i18n-base-zh-cn
* luci-app-ksmbd
* luci-app-upnp
* block-mount
* luci-app-filemanager

### 通过三方渠道🪄
* luci-app-mihomo
* luci-theme-design

$$Custom \quad Settings$$
```html
<style>
.navbar {
  display: none;
}
</style>

<div class="navbar">
  <a href="/cgi-bin/luci/admin/status/overview"><img src="<%=media%>/images/home.png" /></a>
  <a href="/cgi-bin/luci/admin/services/openclash"><img src="<%=media%>/images/openclash.png" /></a>
  <a href="/cgi-bin/luci/admin/network/network"><img src="<%=media%>/images/link.png" /></a>
  <a href="/cgi-bin/luci/admin/status/realtime"><img src="<%=media%>/images/rank.png" /></a>
  <a href="/cgi-bin/luci/admin/system/admin"><img src="<%=media%>/images/user.png" /></a>
</div>
```

`⬇️Download:`
[OpenWrt-NIKKI](https://github.com/nikkinikki-org/OpenWrt-nikki)
[MiHomo](https://github.com/MetaCubeX/mihomo)
[OpeWrt.AI](https://dl.openwrt.ai/packages-24.10/mipsel_24kc/kiddin9/)
[OpenWrt固件插件](https://dllkids.xyz/packages/mipsel_24kc/)

## 🔮选装插件:

- [ ] luci-mod-dashboard
- [ ] [luci-app-diskman](https://github.com/lisaac/luci-app-diskman)
- [x] [luci-app-disks-info](https://github.com/gSpotx2f/luci-app-disks-info)
- [ ] luci-app-aria2
- [ ] luci-app-mwan3
- [ ] luci-app-oaf
- [ ] luci-app-openclash
- [ ] [luci-app-clash](https://github.com/frainzy1477/luci-app-clash)
- [ ] luci-app-frpc
- [ ] tailscale
- [ ] luci-app-zerotier
- [ ] adguardhome
- [ ] luci-app-samba4
- [ ] luci-app-smartdns
- [ ] luci-app-wol
- [ ] luci-app-sqm
- [ ] luci-app-wifidog

<table>
<thead>
<tr>
<th align="left">⚙️ 系统</th>
<th align="left">⚓ 服务</th>
<th align="left">🐳 Docker</th>
<th align="left">🩺 网络</th>
</tr>
</thead>
<tbody><tr>
<td align="left">TTYd</td>
<td align="left">MihomoTProxy</td>
<td align="left">DockerMan</td>
<td align="left">网速测试</td>
</tr>
<tr>
<td align="left">DiskMan</td>
<td align="left">Watchdog</td>
<td align="left">Docker Compose</td>
<td align="left">WireGuard</td>
</tr>
</tbody></table>

## 🔎插件记录:
<details>
<summary><b>&nbsp;精简版本插件预览</b></summary>
<br/>
<img src="https://github.com/Kakile/OpenWrt.R3G/blob/1aadd7355a839bcdab4b627d9815b062f6b50102/Images/mini.png"/>
</details>

<details>
<summary><b>&nbsp;多功能版插件预览</b></summary>
<br/>
<img src="https://github.com/Kakile/OpenWrt.R3G/blob/1aadd7355a839bcdab4b627d9815b062f6b50102/Images/plus.png"/>
</details>

<details>
<summary><b>&nbsp;插件预览</b></summary>
<br/>
<details>
<summary><b>├── 状态</b></summary>
　├── 概况<br/>
　├── 防火墙<br/>
　├── 路由表<br/>
　├── 系统日志<br/>
　├── 内核日志<br/>
　├── 系统进程<br/>
　├── 实时信息<br/>
　├── 实时监控<br/>
　├── 在线用户<br/>
　├── WireGuard 状态<br/>
　├── 负载均衡<br/>
　└── 释放内存
</details>
<details>
<summary><b>├── 系统</b></summary>
　├── 系统<br/>
　├── 管理权<br/>
　├── TTYD 终端<br/>
　├── 软件包<br/>
　├── 启动项<br/>
　├── 计划任务<br/>
　├── 挂载点<br/>
　├── 磁盘管理<br/>
　├── 备份/升级<br/>
　├── 自定义命令<br/>
　├── 定时重启<br/>
　├── 文件传输<br/>
　├── Argon 主题设置<br/>
　├── 重启<br/>
　└── 关机
</details>
<details>
<summary><b>├── 服务</b></summary>
　├── PassWall<br/>
　├── PassWall2<br/>
　├── Hello World<br/>
　├── iKoolProxy 滤广告<br/>
　├── V2ray 服务器<br/>
　├── 广告屏蔽大师 Plus+<br/>
　├── ShadowSocksR Plus+<br/>
　├── AdGuard Home<br/>
　├── 应用过滤<br/>
　├── MosDNS<br/>
　├── 全能推送<br/>
　├── 微信推送<br/>
　├── 上网时间控制<br/>
　├── 解锁网易云灰色歌曲<br/>
　├── OpenClash<br/>
　├── 动态 DNS<br/>
　├── MultiSD_Lite<br/>
　├── SmartDNS<br/>
　├── 网络唤醒<br/>
　├── 迅雷快鸟<br/>
　├── Frps<br/>
　├── UU游戏加速器<br/>
　├── UPnP<br/>
　├── KMS 服务器<br/>
　├── AirPlay 2 音频接收<br/>
　├── udpxy<br/>
　├── Nps 内网穿透<br/>
　├── uHTTPd<br/>
　├── Frp 内网穿透<br/>
　└── MWAN3 分流助手
</details>
<details>
<summary><b>├── Docker</b></summary>
　├── 概览<br/>
　├── 容器<br/>
　├── 镜像<br/>
　├── 网络<br/>
　├── 存储卷<br/>
　├── 事件<br/>
　└── 设置
</details>
<details>
<summary><b>├── 网络存储</b></summary>
　├── 文件浏览器<br/>
　├── 可道云<br/>
　├── NFS 管理<br/>
　├── 微力同步<br/>
　├── Alist 文件列表<br/>
　├── qBittorrent<br/>
　├── USB 打印服务器<br/>
　├── 硬盘休眠<br/>
　├── 挂载 SMB 网络共享<br/>
　├── 网络共享<br/>
　├── FTP 服务器<br/>
　├── Rclone<br/>
　├── Aria2 配置<br/>
　├── miniDLNA<br/>
　└── Transmission
</details>
<details>
<summary><b>├── VPN</b></summary>
　├── N2N v2 VPN<br/>
　├── SoftEther VPN 服务器<br/>
　├── OpenVPN 服务器<br/>
　├── PPTP VPN 服务器<br/>
　├── IPSec VPN 服务器<br/>
　└── ZeroTier
</details>
<details>
<summary><b>├── 网络</b></summary>
　├── 接口<br/>
　├── DHCP/DNS<br/>
　├── 主机名<br/>
　├── IP/MAC 绑定<br/>
　├── 静态路由<br/>
　├── 防火墙<br/>
　├── 诊断<br/>
　├── Socat<br/>
　├── SQM QoS<br/>
　├── 网速控制<br/>
　├── 多线多拨<br/>
　├── 负载均衡<br/>
　└── Turbo ACC 网络加速
</details>
<details>
<summary><b>├── 带宽监控</b></summary>
　├── 显示<br/>
　├── 配置<br/>
　├── 备份<br/>
　├── 网速监控<br/>
　└── 实时流量监测
</details>
　└── <b>退出</b>
</details>
0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟

✨🪄🔎📔🗂️🔥⭐💖⚡🔦🔮🧸

```
luci-theme-design备份来源 @fichenx(https://github.com/fichenx/packages)
同步"上上上上上上上"游更新 (https://github.com/kenzok8/small-package)
GithubPage (https://kenzok8.github.io/openwrt-packages/)
```
[OpenWRT Team](https://github.com/openwrt/openwrt)，[Lean大雕](https://github.com/coolsnowwolf/lede)，[ImmortalWRT Team](https://github.com/immortalwrt/immortalwrt)，[Kiddin9大神](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s-r5s-N1)，[Lienol大神](https://github.com/lienol/openwrt)，[OprX项目](https://www.oprx.top/)，[iStoreOS](https://fw.koolcenter.com/iStoreOS/)

[hackpascal](https://breed.hackpascal.net/)，[hanwckf](https://cmi.hanwckf.top/)，[hiboy](https://opt.cn2qq.com/padavan/)，[XiaoWanSM](https://pan.wwang.pw/)
