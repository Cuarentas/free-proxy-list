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

Last Updated: 2026-01-28 07:25:17 UTC

**Total Proxies: 1879132**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 10 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIMJLC3QWMS5KB3DUBG9HZG1VDMLLLMNUIIWGINBVCNQIOIAINJUWNZAILCAIDHLWZSI6ICJUB25LIIWGIMLKIJOGIJAYNTNINTC0LTGWMJATMZE4NI1HNJQ3LTAYNJCYOTVHYZLIYIISICJHAWQIOIAIMCISICJUZXQIOIAID3MILCAICGF0ACI6ICIVCM9JA2V0IIWGIMHVC3QIOIAIYMVZDDAXLMRVD25SB2FKBW92AWUUY24ILCAIDGXZIJOGIIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogimjlc3qwms5kb3dubg9hzg1vdmlllmnuiiwginbvcnqioiainjuwnzailcaidhlwzsi6icjub25liiwgimlkijogijayntnintc0ltgwmjatmze4ni1hnjq3ltaynjcyotvhyzliyiisicjhawqioiaimcisicjuzxqioiaid3milcaicgf0aci6icivcm9ja2v0iiwgimhvc3qioiaiymvzddaxlmrvd25sb2fkbw92awuuy24ilcaidgxzijogiij9vless.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIMJLC3QWMS5KB3DUBG9HZG1VDMLLLMNUIIWGINBVCNQIOIAINJUWOTUILCAIDHLWZSI6ICJUB25LIIWGIMLKIJOGIJAYNTNINTC0LTGWMJATMZE4NI1HNJQ3LTAYNJCYOTVHYZLIYIISICJHAWQIOIAIMCISICJUZXQIOIAID3MILCAICGF0ACI6ICIVCM9JA2V0IIWGIMHVC3QIOIAIYMVZDDAXLMRVD25SB2FKBW92AWUUY24ILCAIDGXZIJOGIIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogimjlc3qwms5kb3dubg9hzg1vdmlllmnuiiwginbvcnqioiainjuwotuilcaidhlwzsi6icjub25liiwgimlkijogijayntnintc0ltgwmjatmze4ni1hnjq3ltaynjcyotvhyzliyiisicjhawqioiaimcisicjuzxqioiaid3milcaicgf0aci6icivcm9ja2v0iiwgimhvc3qioiaiymvzddaxlmrvd25sb2fkbw92awuuy24ilcaidgxzijogiij9ss.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIJEWNC4XOS41NS40OSISICJWB3J0IJOGMJA4NIWGIMLKIJOGIMU5ZTNJYZEZLWRINDGTNGNJMS04YZI0LTC2MJY0MZLHNTMZOSISICJHAWQIOIAWLCAIC2N5IJOGIMF1DG8ILCAIBMV0IJOGINDZIIWGIMHVC3QIOIAIAXAYLJE0NTCYMZAUEHL6IIWGINBHDGGIOIAIZ2L0AHVILMNVBS9BBHZPBJK5OTKILCAIDGXZIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogijewnc4xos41ns40osisicjwb3j0ijogmja4niwgimlkijogimu5ztnjyzezlwrindgtngnjms04yzi0ltc2mjy0mzlhntmzosisicjhawqioiawlcaic2n5ijogimf1dg8ilcaibmv0ijogindziiwgimhvc3qioiaiaxaylje0ntcymzauehl6iiwginbhdggioiaiz2l0ahvilmnvbs9bbhzpbjk5otkilcaidgxzijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9ss.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIMRHDGETDXMTDJEUC2H3AMZRDY5JBIISICJWB3J0IJOGMJA0MDESICJPZCI6ICJIMTQ3OGUYNC00OTE2LTNHYMUTOGYXNY0XNTKZMTAXMMVJYMUILCAIYWLKIJOGMCWGINNJESI6ICJHDXRVIIWGIM5LDCI6ICJ3CYISICJOB3N0IJOGIMRHDGETDXMTDJEUC2H3AMZRDY5JBIISICJWYXROIJOGII9KZWJPYW4ILCAIDGXZIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogimrhdgetdxmtdjeuc2h3amzrdy5jbiisicjwb3j0ijogmja0mdesicjpzci6icjimtq3oguync00ote2ltnhymutogyxny0xntkzmtaxmmvjymuilcaiywlkijogmcwginnjesi6icjhdxrviiwgim5ldci6icj3cyisicjob3n0ijogimrhdgetdxmtdjeuc2h3amzrdy5jbiisicjwyxroijogii9kzwjpyw4ilcaidgxzijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIBM9KZWPZLM9YZYISICJHAWQIOIAIMCISICJHBHBUIJOGIIISICJMCCI6ICIILCAIAG9ZDCI6ICJOZGZ5MWMXLMNWAWZVCNBLCNNPYS51AYISICJPZCI6ICI2YJG4MGIWNY1LOTUYLTRJMGITYJRHMY02YZLHYZRJZJLKM2YILCAIBMV0IJOGINDZIIWGINBHDGGIOIAIL1F2DHZQZERYWELSU2RATXFUDXHHIIWGINBVCNQIOIAINDQZIIWGINNJESI6ICJHDXRVIIWGINNUASI6ICJOZGZ5MWMXLMNWAWZVCNBLCNNPYS51AYISICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaibm9kzwpzlm9yzyisicjhawqioiaimcisicjhbhbuijogiiisicjmcci6iciilcaiag9zdci6icjozgz5mwmxlmnwawzvcnblcnnpys51ayisicjpzci6ici2yjg4mgiwny1lotuyltrjmgityjrhmy02yzlhyzrjzjlkm2yilcaibmv0ijogindziiwginbhdggioiail1f2dhzqzerywelsu2ratxfudxhhiiwginbvcnqioiaindqziiwginnjesi6icjhdxrviiwginnuasi6icjozgz5mwmxlmnwawzvcnblcnnpys51ayisicj0bhmioiaidgxziiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9ss.txt |
| EYJHZGQIOIAIMTU0LJY0LJIZMI4XODUILCAIYWLKIJOGIJAILCAIYWXWBII6ICIILCAIZNAIOIAIIIWGIMHVC3QIOIAIIIWGIMLKIJOGIJRKOWQXYZM0LWRKOWQTNGYZMS1HZDNILTQ2NWNMNZA5MJC0OSISICJUZXQIOIAID3MILCAICGF0ACI6ICIVIIWGINBVCNQIOIAINDA5MDMILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIIISICJ0BHMIOIAIIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimtu0ljy0ljizmi4xoduilcaiywlkijogijailcaiywxwbii6iciilcaiznaioiaiiiwgimhvc3qioiaiiiwgimlkijogijrkowqxyzm0lwrkowqtngyzms1hzdniltq2nwnmnza5mjc0osisicjuzxqioiaid3milcaicgf0aci6iciviiwginbvcnqioiainda5mdmilcaic2n5ijogimf1dg8ilcaic25pijogiiisicj0bhmioiaiiiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9ss.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXNZIUMJMZLJIYOS45MSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIYN2JHODDMYY01ODNMLTQ3NJMTOTA2MC04M2NMMGI5MJY0ZGIILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJE0MTAYIIWICHMIOILIMPJVUI8GQEZYZWVWAXJHB29STMV0IDKILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziumjmzljiyos45msisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiiyn2jhoddmyy01odnmltq3njmtota2mc04m2nmmgi5mjy0zgiilcjpbnnly3vyzsi6ijailcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ije0mtayiiwichmioilimpjvui8gqezyzwvwaxjhb29stmv0idkilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| HTTP | 469855 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 431518 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 209 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 455219 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 476496 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5299 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 81 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6114 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27149 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7146 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
