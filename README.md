# iptv-cn
## 简介

亲测 **广东** 可用的 IPTV 资源，适用于Jellyfin 的电视直播。

## 如何使用

### 文件说明

`tv-ipv4-cn` => 境内通用 `m3u` 文件

`tv-ipv4-gd` => 广东省内使用，优选 ✅

`tv-ipv4-old` => 参考 [BurningC4](https://github.com/BurningC4/Chinese-IPTV) 的仓库，两年前的原始数据，部分可用，存在延迟和卡顿

### Channel lists (以广东为例)

- **Github**

  `https://raw.githubusercontent.com/frankwuzp/iptv-cn/main/tv-ipv4-gd.m3u`

- **jsDelivr CDN** (CDN 加速，大陆用户可选用)

  `https://cdn.jsdelivr.net/gh/frankwuzp/iptv-cn@latest/tv-ipv4-gd.m3u`

可保存本仓库的 `tv-ipv4-gd.m3u` 文件，或将以上网址（二选一）填入 Jellyfin 的电视直播协调器：

![jellyfin-setting](./image/jellyfin-settings.png)

### Guide file (三选一)

- 大神版

  `http://epg.51zmt.top:8000/e.xml`

- **Github**

  `https://raw.githubusercontent.com/BurningC4/Chinese-IPTV/master/guide.xml`

- **jsDelivr CDN (optimized for mainland users)**

  `https://cdn.jsdelivr.net/gh/BurningC4/Chinese-IPTV@master/guide.xml`

![jellyfin-epg](./image/jellyfin-epg.png)

## 来源

- [BurningC4/Chinese-IPTV](https://github.com/BurningC4/Chinese-IPTV)
- [国内高清直播live - TV001](http://www.tv001.vip/forum.php?mod=viewthread&tid=3)
- [广东移动某河全套 - 恩山无线论坛](https://www.right.com.cn/forum/thread-6809023-1-1.html)

**感谢开放的互联网！🎉🎉🎉**

## Changelog

- 211122 分为国内通用版、广东省内专用版
- 211121 init
