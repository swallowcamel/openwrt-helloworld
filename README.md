# openwrt-helloworld

this applications it's a gift just help you say hello to the world.

## luci app list
- luci-app-clash
- luci-app-openclash
- luci-app-passwall
- luci-app-ssr-plus
- luci-app-smartdns
- luci-app-adguardhome
- luci-app-oaf


All sourcecode from 

https://github.com/Lienol/openwrt-package.git
https://github.com/destan19/OpenAppFilter.git
https://github.com/kenzok8/openwrt-packages.git
https://github.com/kenzok8/small.git

This source code is only guaranteed to compile successfully on [openwrt v19.07.3](https://github.com/openwrt/openwrt.git), if you are using other source code compilation, error please solve yourself.

Please do not send junk issue and junk PR, otherwise direct ban.

Add "src-git helloworld https://github.com/swallowcamel/openwrt-helloworld" to feeds.conf.default.

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```

Or download it yourself and put it in the package folder.
make after enjoy...

If you use Luci-19 or higher, Please selected the "luci-compat" and "luci-lib-ipkg" before compile
