## 说明
1. 定时从上游各规则源获取更新，合并去重。
2. 使用国内、国外各 3 组 DNS 服务，分别对上游各规则源拦截的域名进行解析，去除已无法解析的域名。
3. 本项目仅对上游规则进行合并、去重、去除无效域名，不做任何修改。如发现误拦截情况，可临时添加放行规则（如 `@@||www.example.com^$important`），并向上游规则反馈。

## 订阅链接
1. AdGuard Home 等 DNS 拦截服务使用规则1
2. AdGuard 等浏览器插件使用规则1 + 规则2（规则2为规则1的补充，仅适用浏览器插件）
3. 规则1’、2’为规则1、2的 Lite 版，仅针对国内域名拦截，体积较小（如添加完整规则报错数量限制，请尝试 Lite 规则）
4. 已对 jsdelivr 缓存进行主动刷新，但 jsdelivr 加速链接仍存在一定延时

| 规则 | 原始链接 | 加速链接1 | 加速链接2 | 加速链接3 | 适配说明 |
|:-|:-|:-|:-|:-|:-|
| 规则1 | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdns.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/adblockdns.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdns.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdns.txt) | AdGuard、AdGuard Home 等 |
| 规则1' | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdnslite.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/adblockdnslite.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdnslite.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdnslite.txt) | AdGuard、AdGuard Home 等 |
| 规则2 | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilters.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/adblockfilters.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilters.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilters.txt) | AdGuard 等 |
| 规则2' | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilterslite.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/adblockfilterslite.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilterslite.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilterslite.txt) | AdGuard 等 |

## 上游规则源
感谢各位广告过滤规则维护大佬们的辛苦付出。

| 规则 | 类型 | 原始链接 | 加速链接1 | 加速链接2 | 加速链接3 | 更新日期 |
|:-|:-|:-|:-|:-|:-|:-|
| AdguardTeam_DNS-Filter | dns | [原始链接](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/AdguardTeam_DNS-Filter.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/AdguardTeam_DNS-Filter.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/AdguardTeam_DNS-Filter.txt) | 2025/02/24 |
| TG-Twilight_AWAvenue-Ads-Rule | dns | [原始链接](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/TG-Twilight_AWAvenue-Ads-Rule.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/TG-Twilight_AWAvenue-Ads-Rule.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/TG-Twilight_AWAvenue-Ads-Rule.txt) | 2025/02/19 |
| d3ward_Toolz | dns | [原始链接](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/d3ward_Toolz.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/d3ward_Toolz.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/d3ward_Toolz.txt) | 2025/01/13 |
| malware-filter_Malicious-URL-Blocklist | dns | [原始链接](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh-online.txt) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/malware-filter_Malicious-URL-Blocklist.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/malware-filter_Malicious-URL-Blocklist.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/malware-filter_Malicious-URL-Blocklist.txt) | 2025/02/24 |
| jdlingyu_ad-wars | host | [原始链接](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts) | [加速链接1](https://gcore.jsdelivr.net/gh/C9LG/DNS-Blocklists@main/rules/jdlingyu_ad-wars.txt) | [加速链接2](https://github.boki.moe/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/jdlingyu_ad-wars.txt) | [加速链接3](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/jdlingyu_ad-wars.txt) | 2025/01/13 |

