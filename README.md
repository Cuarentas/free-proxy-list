<p align="center">
  <img src="https://img.shields.io/badge/Updated_Every_30_Minutes-passing-success">  
  <br>
  <img src="https://img.shields.io/website/https/getfreeproxy.com.svg">
  <img src="https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/total.svg">
  <img src="https://img.shields.io/github/last-commit/gfpcom/free-proxy-list.svg">
  <img src="https://img.shields.io/github/license/gfpcom/free-proxy-list.svg">
  
  <br>
  <br>
  <a href="https://getfreeproxy.com/lists/" title="free working proxy list">Working Proxy List</a> | <a href="https://getfreeproxy.com/tools/proxy-checker" title="free online proxy checker">Free Proxy Checker</a> | <a href="https://getfreeproxy.com/tools/proxy-protocol-parser" title="free online proxy protocol parser">Universal Proxy Procotol Parser</a>
  <br>
</p>

# 🌎 GetFreeProxy (GFP): Free Proxy List

**GetFreeProxy (GFP)** is an open-source project that automatically aggregates and validates free proxies from across the internet. Our goal is to provide a fresh, reliable, and comprehensive list of public proxies for developers, researchers, and anyone in need of proxy services.

The lists are updated hourly, ensuring you always have access to the most current proxies available.

## 🔄 How It Works

This project runs on a simple yet powerful automated workflow:

1.  **Fetch**: A Go application fetches proxy lists from various sources defined in the `sources/` directory. It supports dynamic URL generation (e.g., based on the current date) and can handle different data formats like raw text, Base64, etc.
2.  **Parse & Normalize**: The fetched data is parsed and normalized into a standard proxy format. The system is extensible, allowing new parsers and data transformers to be added easily.
3.  **Deduplicate & Store**: All unique proxies are stored in memory.
4.  **Generate Lists**: The application generates clean, protocol-specific proxy lists (e.g., `http.txt`, `vless.txt`) and saves them in the `list/` directory.
5.  **Update Badges**: SVG badges are generated to display the count of available proxies for each protocol.

This entire process is automated using GitHub Actions and runs every hour.

## 📋 Proxy Formats

We provide proxies in multiple formats, ready to be used in your applications.

| Type | Format | Example |
| :--- | :--- | :--- |
| **HTTP/S** | `http://ip:port` | `http://1.2.3.4:8080` |
| | `http://user:pass@ip:port` | `http://user:pass@1.2.3.4:8080` |
| **SOCKS4/5** | `socks5://ip:port` | `socks5://1.2.3.4:1080` |
| **V2Ray/XRay**| `vmess://...` / `vless://...` | `vless://uuid@...` |
| **Trojan** | `trojan://...` | `trojan://uuid@...` |
| **ShadowSocks**| `ss://...` / `ssr://...` | `ss://method:pass@...` |
| **Hysteria** | `hy://...` (*Note: `hysteria://`, `hhysteria://` are automatically converted to `hy://`) | `hy://uuid@...` |
| **Hysteria2**| `hy2://...` (*Note: `hysteria2://`, `hhy2://`, `hhysteria2://` are automatically converted to `hy2://`) | `hy2://uuid@...` |
| **TUIC**| `tuic://...` | `tuic://uuid@...` |
| **WireGuard**| `wireguard://...` | `wireguard://publickey@endpoint:port?allowed_ips=...` |

## 🔗 Direct Download Links


Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

<!-- BEGIN PROXY LIST -->

Last Updated: 2026-01-24 01:26:18 UTC

**Total Proxies: 1908826**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJHZGQIOIAICY5TYXJRDHJLZC5JB20ILCAIYWLKIJOGIJAILCAIYWXWBII6ICIILCAIZNAIOIAIIIWGIMHVC3QIOIAIYXZLAXJVCI5JB20ILCAIAWQIOIAIMDNMY2M2MTGTYJKZZC02NZK2LTZHZWQTOGEZOGM5NZVKNTGXIIWGIM5LDCI6ICJ3CYISICJWYXROIJOGII9SAW5RDNDZIIWGINBVCNQIOIAINDQZIIWGINNJESI6ICJHDXRVIIWGINNUASI6ICJHDMVPCM9YLMNVBSISICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaicy5tyxjrdhjlzc5jb20ilcaiywlkijogijailcaiywxwbii6iciilcaiznaioiaiiiwgimhvc3qioiaiyxzlaxjvci5jb20ilcaiawqioiaimdnmy2m2mtgtyjkzzc02nzk2ltzhzwqtogezogm5nzvkntgxiiwgim5ldci6icj3cyisicjwyxroijogii9saw5rdndziiwginbvcnqioiaindqziiwginnjesi6icjhdxrviiwginnuasi6icjhdmvpcm9ylmnvbsisicj0bhmioiaidgxziiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII0NS44OC4XODMUMTG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIILCJPZCI6IJUXODQ4YJJJLTGWMJYTNDEYZS05ZJA2LTLIMMI1ZWNKMTCWOCISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II8ILCJWB3J0IJOINDQZIIWICHMIOIJAVNBUTWFHBNWZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii0ns44oc4xodmumtg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiilcjpzci6ijuxodq4yjjjltgwmjytndeyzs05zja2ltlimmi1zwnkmtcwocisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii8ilcjwb3j0ijoindqziiwichmioijavnbutwfhbnwziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII1LJE2MC4XOTCUNZGILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIY2HYB21LIIWIAG9ZDCI6IND3DY52YXJ6ZXNOMY5JB20ILCJPZCI6IMFHN2RKOTZIMGE3ZDGXZGIYZTCXNTUZYWJLMTKYNJIWIIWIBMV0IJOIDGNWIIWICGF0ACI6II8ILCJWB3J0IJOIMTC1NJQILCJWCYI6IVCFLLBARMFZDF8YCMF5IPCFKYJYS9IX2YJYSDMH2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IMH0DHAILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii1lje2mc4xotcunzgilcjhawqioiiwiiwiywxwbii6iiisimzwijoiy2hyb21liiwiag9zdci6ind3dy52yxj6zxnomy5jb20ilcjpzci6imfhn2rkotzimge3zdgxzgiyztcxntuzywjlmtkynjiwiiwibmv0ijoidgnwiiwicgf0aci6ii8ilcjwb3j0ijoimtc1njqilcjwcyi6ivcfllbarmfzdf8ycmf5ipcfkyjys9ix2yjysdmh2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6imh0dhailcj2ijoimij9vless.txt |
| EYJHZGQIOII4MS4XMI4ZMY4XODIILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6INBHCNNHYNIUY29TIIWIAWQIOIIXNMVIZTI1ZI02NTI0LTQ3OWITOGQWYY1LYTLKNZQ2OGNMYZKILCJUZXQIOIJ0Y3AILCJWYXROIJOIL2FWAS9YZWDPC3RLCI9UZXCVBMFTZS9KYXYVCMVZCG9UC2UVY21WMGFYSMXAQ0JVWLD4C2J5QM9IM2NNWVHKBELIBHZKU0IWYUDSEKLHBHPJRZE1SUC1BGR5QM9AV0ZRWLHJZ2QILCJWB3J0IJOIMJAYNCISINBZIJOIQEDVBGVZDGFUX1ZQTIATIPCFN6IILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IMH0DHAILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii4ms4xmi4zmy4xodiilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6inbhcnnhyniuy29tiiwiawqioiixnmvizti1zi02nti0ltq3owitogqwyy1lytlknzq2ognmyzkilcjuzxqioij0y3ailcjwyxroijoil2fwas9yzwdpc3rlci9uzxcvbmftzs9kyxyvcmvzcg9uc2uvy21wmgfysmxaq0jvwld4c2j5qm9im2nnwvhkbelibhzku0iwyudseklhbhpjrze1suc1bgr5qm9av0zrwlhjz2qilcjwb3j0ijoimjayncisinbzijoiqedvbgvzdgfux1zqtiatipcfn6iilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6imh0dhailcj2ijoimij9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| HTTP | 477625 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 438755 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 226 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 463217 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 483010 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5370 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 82 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6041 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 4 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27408 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7056 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
| WIREGUARD | 17 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/wireguard.txt |

<!-- END PROXY LIST -->

## 🤝 Contributing

This is a community-driven project, and your contributions are highly welcome! The easiest way to contribute is by adding new proxy sources.

Please read our **[Contributing Guidelines](CONTRIBUTING.md)** to get started.

## 🙏 Support the Project

If you find this project useful, please consider supporting it. It helps us gain visibility and encourages more people to contribute.

-   **Star this repository** on GitHub! ⭐️
-   **Share it** with your friends and colleagues.

## ⚠️ Disclaimer

-   These proxies are collected from public sources. There is no guarantee of their speed, security, or uptime.
-   Use these proxies at your own risk.
-   The maintainers of this repository are not responsible for any misuse. Do not use these proxies for illegal activities.

## 📝 License

This repository is released under the MIT license. See [LICENSE](LICENSE) for details.
