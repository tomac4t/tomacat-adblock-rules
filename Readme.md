## 私人广告屏蔽规则

- [`DNS-blacklist.txt`](DNS-blacklist.txt): Adguard Home 自定义过滤规则。作为以下规则的补充（已做去重处理）。一些规则会上报到上游 [AdguardFilters](https://github.com/AdguardTeam/AdguardFilters)，故一些规则去重后会删除。这些规则本着尽可能不破坏正常使用的情况下加入广告和追踪域名，规则比较保守但略偏激进，会加入一些可疑的域名，若不影响正常使用，则不会删除。
  - [AdGuard DNS filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)
  - [AdAway Default Blocklist](https://adaway.org/hosts.txt)
  - [WindowsSpyBlocker - Hosts spy rules](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt)
  - neohosts: https://raw.githubusercontent.com/neoFelhz/neohosts/gh-pages/basic/hosts.txt
- [`uMatrix-rules.txt`](uMatrix-rules.txt): uMatrix 规则集，并作为以下 Hosts 规则的补充（已做去重处理）。覆盖了国内外常见网站的访问情况，加入但是最近去除了 Disquc (https://github.com/tomac4t/tomacat-adblock-rules/commit/3596efe9c0b852d9415fc9b99d2e8adee7c0b677) 的全局规则，原因是它严重拖慢网站访问速度，其次它是中心化平台隐私不友好，背离了本规则的初衷。本规则在会在隐私和不破坏网站的情况下做出平衡，目前已加入常见前端公共库域名、常见验证码平台域名作为全局规则。
  - Dan Pollock’s hosts file
  - Peter Lowe’s Ad and tracking server list
  - https://adaway.org/hosts.txt
  - https://cdn.jsdelivr.net/gh/neoFelhz/neohosts@gh-pages/basic/hosts.txt
  - https://raw.githubusercontent.com/r-a-y/mobile-hosts/master/AdguardDNS.txt
- [`DNS-blacklist-ISPonekey.txt`](DNS-blacklist-ISPonekey.txt)：收集自网络的三大运营商一键登录的域名，我的客观条件只能收集到中国移动，所以…按需使用吧。

安全性提示：AdGuard Home 的规则支持 DNS 重写，添加第三方过滤规则需要注意潜在的安全问题。