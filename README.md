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

Last Updated: 2026-01-31 19:42:07 UTC

**Total Proxies: 1824210**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIMLUZ3JLC3MTATEUB25LYM94NI5VCMCILCAICG9YDCI6ICIZODIWMSISICJ0EXBLIJOGIM5VBMUILCAIAWQIOIAINZKZODY2ODUTMTZKYS0ZMJDJLTLLMTQTYWE2ZDCWMMQ4NMJJIIWGIMFPZCI6ICIWIIWGIM5LDCI6ICJ3CYISICJWYXROIJOGII9OBHMVY2N0DJVWAGQUBTN1OCISICJOB3N0IJOGIMLUZ3JLC3MTATEUB25LYM94NI5VCMCILCAIDGXZIJOGIIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogimluz3jlc3mtateub25lym94ni5vcmcilcaicg9ydci6icizodiwmsisicj0exblijogim5vbmuilcaiawqioiainzkzody2odutmtzkys0zmjdjltllmtqtywe2zdcwmmq4nmjjiiwgimfpzci6iciwiiwgim5ldci6icj3cyisicjwyxroijogii9obhmvy2n0djvwagqubtn1ocisicjob3n0ijogimluz3jlc3mtateub25lym94ni5vcmcilcaidgxzijogiij9vless.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIJE3MI42NC4XNZUUODGILCAICG9YDCI6IDIWODYSICJPZCI6ICJLOWUZY2MXMY1KYJQ4LTRJYZETOGMYNC03NJI2NDM5YTUZMZKILCAIYWLKIJOGMCWGINNJESI6ICJHDXRVIIWGIM5LDCI6ICJ3CYISICJOB3N0IJOGIMLWMTQUZNJLZWDYYWRLBHKUEHL6IIWGINBHDGGIOIAIZ2L0AHVILMNVBS9BBHZPBJK5OTKILCAIDGXZIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogije3mi42nc4xnzuuodgilcaicg9ydci6idiwodysicjpzci6icjlowuzy2mxmy1kyjq4ltrjyzetogmync03nji2ndm5ytuzmzkilcaiywlkijogmcwginnjesi6icjhdxrviiwgim5ldci6icj3cyisicjob3n0ijogimlwmtquznjlzwdyywrlbhkuehl6iiwginbhdggioiaiz2l0ahvilmnvbs9bbhzpbjk5otkilcaidgxzijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIJEWNC4XOS41NS40OSISICJWB3J0IJOGMJA4NIWGIMLKIJOGIMU5ZTNJYZEZLWRINDGTNGNJMS04YZI0LTC2MJY0MZLHNTMZOSISICJHAWQIOIAWLCAIC2N5IJOGIMF1DG8ILCAIBMV0IJOGINDZIIWGIMHVC3QIOIAIAXAYLJE0NTCYMZAUEHL6IIWGINBHDGGIOIAIZ2L0AHVILMNVBS9BBHZPBJK5OTKILCAIDGXZIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogijewnc4xos41ns40osisicjwb3j0ijogmja4niwgimlkijogimu5ztnjyzezlwrindgtngnjms04yzi0ltc2mjy0mzlhntmzosisicjhawqioiawlcaic2n5ijogimf1dg8ilcaibmv0ijogindziiwgimhvc3qioiaiaxaylje0ntcymzauehl6iiwginbhdggioiaiz2l0ahvilmnvbs9bbhzpbjk5otkilcaidgxzijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9ss.txt |
| EYJHZGQIOIAIMTA0LJE5LJQ1LJC5IIWGIMFPZCI6IDASICJOB3N0IJOGIMHRMDEUBGVSZWXLCY51CYISICJPZCI6ICIZOTEZNWEZOS1LNMNHLTQZZGYTYTM2MC1KODU5ZWVHNTHKODYILCAIBMV0IJOGINDZIIWGINBHDGGIOIAILYISICJWB3J0IJOGODQ0MYWGINRSCYI6ICJ0BHMILCAIDHLWZSI6ICJHDXRVIIWGINNLY3VYAXR5IJOGIMF1DG8ILCAIC2TPCC1JZXJ0LXZLCMLMESI6IGZHBHNLLCAIC25PIJOGIMHRMDEUBGVSZWXLCY51CYISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje5ljq1ljc5iiwgimfpzci6idasicjob3n0ijogimhrmdeubgvszwxlcy51cyisicjpzci6icizoteznwezos1lnmnhltqzzgytytm2mc1kodu5zwvhnthkodyilcaibmv0ijogindziiwginbhdggioiailyisicjwb3j0ijogodq0mywginrscyi6icj0bhmilcaidhlwzsi6icjhdxrviiwginnly3vyaxr5ijogimf1dg8ilcaic2tpcc1jzxj0lxzlcmlmesi6igzhbhnllcaic25pijogimhrmdeubgvszwxlcy51cyisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIMTA0LJE5LJQ3LJIYNIISICJHAWQIOIAWLCAIAG9ZDCI6ICJOAZAXLMXPBMTPDG5VDY5UZXQILCAIAWQIOIAIMZKXMZVHMZKTZTZJYS00M2RMLWEZNJATZDG1OWVLYTU4ZDG2IIWGIM5LDCI6ICJ3CYISICJWYXROIJOGII8ILCAICG9YDCI6IDG0NDMSICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIYXV0BYISICJZZWN1CML0ESI6ICJHDXRVIIWGINNRAXATY2VYDC12ZXJPZNKIOIB0CNVLLCAIC25PIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje5ljq3ljiyniisicjhawqioiawlcaiag9zdci6icjoazaxlmxpbmtpdg5vdy5uzxqilcaiawqioiaimzkxmzvhmzktztzjys00m2rmlweznjatzdg1owvlytu4zdg2iiwgim5ldci6icj3cyisicjwyxroijogii8ilcaicg9ydci6idg0ndmsicj0bhmioiaidgxziiwginr5cguioiaiyxv0byisicjzzwn1cml0esi6icjhdxrviiwginnraxaty2vydc12zxjpznkioib0cnvllcaic25pijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIMTUXLJEWMS4XOTMUNTCILCAIYWLKIJOGIJAILCAIYWXWBII6ICIILCAIZNAIOIAIIIWGIMHVC3QIOIAIRGJKAMHPDZCYZWJZDTI3MMHZNTE5AI5JB20ILCAIAWQIOIAIYJDKYWUYMTETNZQ3MI00OGJMLTK5NMMTNTDKNJUZOGQXZWY0IIWGIM5LDCI6ICJ3CYISICJWYXROIJOGINDZLZ9LZD0YMDQ4IIWGINBVCNQIOIAIODAILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIIISICJ0BHMIOIAIIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimtuxljewms4xotmuntcilcaiywlkijogijailcaiywxwbii6iciilcaiznaioiaiiiwgimhvc3qioiairgjkamhpdzcyzwjzdti3mmhznte5ai5jb20ilcaiawqioiaiyjdkywuymtetnzq3mi00ogjmltk5nmmtntdknjuzogqxzwy0iiwgim5ldci6icj3cyisicjwyxroijogindzlz9lzd0ymdq4iiwginbvcnqioiaiodailcaic2n5ijogimf1dg8ilcaic25pijogiiisicj0bhmioiaiiiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIJJBG91ZC5UZXH1BI5PCIISIMFPZCI6IJAILCJHBHBUIJOIADIILCJMCCI6IMNOCM9TZSISIMHVC3QIOIJHCNMUBMV4DW4UAXIILCJPZCI6IMNMMDAWNDAZLTFHNMITNDNJNS1IMDDMLTVLN2M3OTQ5YJRKYYISIMLUC2VJDXJLIJOIMCISIM5LDCI6INHODHRWIIWICGF0ACI6II9LY29IVFRQIIWICG9YDCI6IJQ0MYISINBZIJOIQGLJDJJYYXKILCJZY3KIOIJHDXRVIIWIC25PIJOIYXJZLM5LEHVULMLYIIWIDGXZIJOIDGXZIIWIDHLWZSI6IMF1DG8ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijjbg91zc5uzxh1bi5pciisimfpzci6ijailcjhbhbuijoiadiilcjmcci6imnocm9tzsisimhvc3qioijhcnmubmv4dw4uaxiilcjpzci6imnmmdawndazltfhnmitndnjns1imddmltvln2m3otq5yjrkyyisimluc2vjdxjlijoimcisim5ldci6inhodhrwiiwicgf0aci6ii9ly29ivfrqiiwicg9ydci6ijq0myisinbzijoiqgljdjjyyxkilcjzy3kioijhdxrviiwic25pijoiyxjzlm5lehvulmlyiiwidgxzijoidgxziiwidhlwzsi6imf1dg8ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJMB3JJZTYUZ29SZHNWZWVKLM9YZYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOILZ9CSUFFVEVMRUDSQU1ATUFSQU1CQVNISV9NQVJBTUJBU0HJX01BUKFNQKFTSELFTUFSQU1CQVNISV9NQVJBTUJBU0HJIIWIAWQIOIJIMDI3ZMIYNS1MN2ZILTRLNGETOTRINS1LNZI2NZFJOGZHMJKILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIILCJWB3J0IJOINTG5NZIILCJWCYI6IKBNQVJBTUJBU0HJIPCFMLBIGI3WN4YR77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmb3jjztyuz29szhnwzwvklm9yzyisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoilz9csuffvevmrudsqu1atufsqu1cqvnisv9nqvjbtujbu0hjx01bukfnqkftselftufsqu1cqvnisv9nqvjbtujbu0hjiiwiawqioijimdi3zmiyns1mn2ziltrlngetotrins1lnzi2nzfjogzhmjkilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiiilcjwb3j0ijointg5nziilcjwcyi6ikbnqvjbtujbu0hjipcfmlbigi3wn4yr77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJOVZEUEMT2BY50B3AILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYZEYYTU4MMITYZJLMS00OTRLLWIXYWMTMTG1ZDQ0YZI5NTJMIIWIBMV0IJOIDGNWIIWICGF0ACI6IIISINBVCNQIOIIYMDKWIIWICHMIOIJAYXBWC29VBMVYINQP2KFZHTIN2YQG2KRZHNQV2LHYP9MFIPCFLYRVUI8ILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijovzeuemt2by50b3ailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiyzeyytu4mmityzjlms00otrllwixywmtmtg1zdq0yzi5ntjmiiwibmv0ijoidgnwiiwicgf0aci6iiisinbvcnqioiiymdkwiiwichmioijayxbwc29vbmvyinqp2kfzhtin2yqg2krzhnqv2lhyp9mfipcflyrvui8ilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| HTTP | 458790 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 419922 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 239 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 443780 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 455908 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5265 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 81 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6042 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 26967 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7176 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
