## 私人广告屏蔽规则

- [`AdguardHome-DNS-blacklist.txt`](AdguardHome-DNS-blacklist.txt): 适用于 AdguardHome，但不存在于下列规则 [`AdGuard DNS filter`](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)、[`AdAway Default Blocklist`](https://adaway.org/hosts.txt) 和 [`neohosts`](https://raw.githubusercontent.com/neoFelhz/neohosts/gh-pages/basic/hosts.txt)，且向 Adguard 提交规则但未被接受的。
- [`my-umatrix-rules.txt`](my-umatrix-rules.txt): uMatrix 规则集，并作为以下 Hosts 规则的补充（去重处理）。
  - Dan Pollock’s hosts file
  - Peter Lowe’s Ad and tracking server list
  - https://adaway.org/hosts.txt
  - https://cdn.jsdelivr.net/gh/neoFelhz/neohosts@gh-pages/basic/hosts.txt
  - https://raw.githubusercontent.com/r-a-y/mobile-hosts/master/AdguardDNS.txt