# AdBlock DNS Filters
适用于AdGuard的去广告规则，每8个小时更新一次。
## 说明
1. 定时从上游各规则源获取更新，合并去重。
2. 使用两组国内、两组国外 DNS 服务，分别对上游各规则源拦截的域名进行解析，去除已无法解析的域名。（上游各规则源中存在大量已无法解析的域名，无需加入拦截规则）
3. 本项目仅对上游规则进行合并、去重、去除无效域名，不做任何修改。如发现误拦截情况，可临时添加放行规则（如 `@@||www.example.com^$important`），并向上游规则反馈。

## 订阅链接
1. AdGuard Home 等DNS拦截服务使用规则1
2. AdGuard 等浏览器插件使用规则1 + 规则2

| 规则 | 原始链接 | 加速链接 |
|:-|:-|:-|
| 规则1：DNS 拦截 | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdns.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockdns.txt) |
| 规则2：插件拦截 | [原始链接](https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilters.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/adblockfilters.txt) |
## 上游规则源
感谢以下大佬们的辛苦付出！

| 规则 | 类型 | 原始链接 | 加速链接 | 更新日期 |
|:-|:-|:-|:-|:-|
| AdguardTeam_DNS-Filter | dns | [原始链接](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/AdguardTeam_DNS-Filter.txt) | 2024/06/15 |
| TG-Twilight_AWAvenue-Ads-Rule | dns | [原始链接](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/TG-Twilight_AWAvenue-Ads-Rule.txt) | 2024/06/08 |
| privacy-protection-tools_anti-AD | dns | [原始链接](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-easylist.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/privacy-protection-tools_anti-AD.txt) | 2024/06/14 |
| UnknownSource_DNS-Rules | dns | [原始链接](https://raw.githubusercontent.com/C9LG/Rules/main/rules.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/UnknownSource_DNS-Rules.txt) | 2024/06/10 |
| malware-filter_Malicious-URL-Blocklist | dns | [原始链接](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh-online.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/malware-filter_Malicious-URL-Blocklist.txt) | 2024/06/15 |
| jdlingyu_ad-wars | host | [原始链接](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/jdlingyu_ad-wars.txt) | 2024/06/08 |
| StevenBlack_(UnifiedHosts) | host | [原始链接](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/gambling/hosts) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/StevenBlack_(UnifiedHosts).txt) | 2024/06/09 |
| xinggsf_MV | filter | [原始链接](https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/mv.txt) | [加速链接](https://mirror.ghproxy.com/https://raw.githubusercontent.com/C9LG/DNS-Blocklists/main/rules/xinggsf_MV.txt) | 2024/06/13 |
