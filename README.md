# adguard-cn-filter

AdGuard DNS filter for blocking ads in Chinese apps — **1,118 rules** (174 precise + 944 upstream, deduplicated).

## 订阅地址 / Subscription URLs

- **jsDelivr（国内推荐，较快）**
  `https://fastly.jsdelivr.net/gh/philechen-eng/adguard-cn-filter@main/adguard-dns-full.txt`

- **GitHub Raw（备用）**
  `https://raw.githubusercontent.com/philechen-eng/adguard-cn-filter/main/adguard-dns-full.txt`

## 用法 / Usage

AdGuard for iOS:

`保护 → DNS 保护（开启，DNS 实现选 AdGuard）→ DNS 过滤 → DNS 过滤器 → 添加过滤器 → 粘贴上面的 URL`

AdGuard for Mac（系统级）:

`首选项 → DNS → 过滤器 → + → 粘贴上面的 URL`

> 只做 DNS 层拦截；抖音、淘宝、B 站等自营广告与内容同域，DNS 无法单独拦截。
