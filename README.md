![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=kenzok8&show_icons=true&theme=radical)
<div align="center">
<h1 align="center"openwrt-packages</h1>
<img src="https://img.shields.io/github/issues/kenzok8/openwrt-packages?color=green">
<img src="https://img.shields.io/github/stars/kenzok8/openwrt-packages?color=yellow">
<img src="https://img.shields.io/github/forks/kenzok8/openwrt-packages?color=orange">
<img src="https://img.shields.io/github/license/kenzok8/openwrt-packages?color=ff69b4">
<img src="https://img.shields.io/github/languages/code-size/kenzok8/openwrt-packages?color=blueviolet">
</div>

<img src="https://v2.jinrishici.com/one.svg?font-size=24&spacing=2&color=Black">

#### 说明

* 喜欢追新的可以去下载small-package，该仓库每天自动同步更新

* [small-package仓库地址](https://github.com/kenzok8/small-package) 

* 软件不定期同步大神库更新，适合一键下载用于openwrt编译


##### 插件每日更新下载:
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kenzok8/compile-package?style=for-the-badge&label=插件更新下载)](https://github.com/kenzok8/compile-package/releases/latest)

+ [passwall依赖](https://github.com/kenzok8/small)

+ [xiaorouji仓库](https://github.com/xiaorouji/openwrt-passwall)

+ 谢谢 **kiddin9珠玉在前**[openwrt固件与插件下载](https://op.dllkids.xyz/op/firmware/)

#### 使用
一键命令
```yaml
sed -i '$a src-git kenzo https://github.com/kenzok8/openwrt-packages' feeds.conf.default
sed -i '$a src-git small https://github.com/kenzok8/small' feeds.conf.default
git pull
./scripts/feeds update -a
./scripts/feeds install -a
make menuconfig
```

- openwrt 固件编译自定义主题与软件
- luci-app-vssr            ------------------vssr老竭力
- luci-app-dnsfilter       ------------------基于DNS的广告过滤
- luci-app-openclash       ------------------openclash图形         
- luci-app-advanced       ------------------系统高级设置
- luci-app-pushbot         ------------------微信/钉钉 推送的插件
- luci-theme-ifit          ------------------透明主题（适配18.06修复主机名错误）
- luci-theme-atmaterial_new  ------------------atmaterial 三合一主题（适配18.06）     
- luci-app-aliddns         ------------------阿里云ddns
- luci-app-eqos            ------------------依IP地址限速
- luci-app-gost            ------------------隐蔽的https代理
- luci-app-adguardhome     ------------------去广告 
- luci-app-smartdns        ------------------smartdns防污染
- luci-app-passwall        ------------------Lienol大神 
- luci-theme-argonne       ------------------修改老竭力主题名
- luci-app-argonne-config  ------------------argonne主题设置
- luci-app-ssr-plus        ------------------Lean大神 
- luci-theme-mcat          ------------------修改主题名  
- luci-theme-tomato        ------------------修改主题名

* 修改argon为argonne，包括argonne-config，为防止同名argon，而影响编译

![暗黄主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-9.jpg)
![暗黄主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-10.jpg)
![暗黄主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-11.jpg)
![暗黑红主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-5.jpg)
![暗黑红主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-6.jpg)
![暗黑红主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-7.jpg)
![暗黑红主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-8.jpg)
![抹茶绿主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-12.jpg)
![抹茶绿主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-13.jpg)
![抹茶绿主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-14.jpg)
![argon主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-1.png)
![argon主题](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/sshot-2.png)
* 修复opentomato 与opentomcat修改主机名无效的bug
![修复tomto不能修改主机名的bug](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-719.png)
![修复tomto不能修改主机名的bug](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-722.png)
![修复cat不能修改主机名的bug](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-720.png)
![修复cat不能修改主机名的bug](https://raw.githubusercontent.com/kenzok8/kenzok8/main/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-721.png)

# openwrt-packages
