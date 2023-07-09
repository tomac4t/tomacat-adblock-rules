## 私人广告屏蔽规则

- [`DNS-blacklist.txt`](DNS-blacklist.txt): AdguardHome 自定义过滤规则。作为以下规则的补充（已做去重处理）。一些规则会上报到上游 [AdguardFilters](https://github.com/AdguardTeam/AdguardFilters)，故一些规则去重后会删除。
  - [AdGuard DNS filter](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)
  - [AdAway Default Blocklist](https://adaway.org/hosts.txt)
  - [WindowsSpyBlocker - Hosts spy rules](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt)
  - neohosts: https://raw.githubusercontent.com/neoFelhz/neohosts/gh-pages/basic/hosts.txt
- [`uMatrix-rules.txt`](my-umatrix-rules.txt): uMatrix 规则集，并作为以下 Hosts 规则的补充（已做去重处理）。
  - Dan Pollock’s hosts file
  - Peter Lowe’s Ad and tracking server list
  - https://adaway.org/hosts.txt
  - https://cdn.jsdelivr.net/gh/neoFelhz/neohosts@gh-pages/basic/hosts.txt
  - https://raw.githubusercontent.com/r-a-y/mobile-hosts/master/AdguardDNS.txt
- [`DNS-blacklist-ISPonekey.txt`](DNS-blacklist-ISPonekey.txt)：收集自网络的三大运营商一键登录的域名。