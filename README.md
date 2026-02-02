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

Last Updated: 2026-02-02 07:00:51 UTC

**Total Proxies: 1870158**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJHZGQIOIAIENVSYS5PCIISICJHAWQIOIAIMCISICJHBHBUIJOGIMGYLGH0DHAVMS4XIIWGIMZWIJOGIMNOCM9TZSISICJOB3N0IJOGIMTPBMDVLMHPZ2H0ZWNOC2VYDMLJZS5PCIISICJPZCI6ICIYNMI5YZRJZS0XYTI1LTRKOGUTYJI2NS0XN2VKNDVHYZVMMTIILCAIBMV0IJOGINDZIIWGINBHDGGIOIAILYISICJWB3J0IJOGIJIWOTYILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIMTPBMDVLMHPZ2H0ZWNOC2VYDMLJZS5PCIISICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaienvsys5pciisicjhawqioiaimcisicjhbhbuijogimgylgh0dhavms4xiiwgimzwijogimnocm9tzsisicjob3n0ijogimtpbmdvlmhpz2h0zwnoc2vydmljzs5pciisicjpzci6iciynmi5yzrjzs0xyti1ltrkogutyji2ns0xn2vkndvhyzvmmtiilcaibmv0ijogindziiwginbhdggioiailyisicjwb3j0ijogijiwotyilcaic2n5ijogimf1dg8ilcaic25pijogimtpbmdvlmhpz2h0zwnoc2vydmljzs5pciisicj0bhmioiaidgxziiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIMTA0LJE5LJQ3LJIWIIWGIMFPZCI6ICIWIIWGIMFSCG4IOIAIIIWGIMZWIJOGIIISICJOB3N0IJOGIMHRMDEUBGLUA2L0BM93LM5LDCISICJPZCI6ICIZOTEZNWEZOS1LNMNHLTQZZGYTYTM2MC1KODU5ZWVHNTHKODYILCAIBMV0IJOGINDZIIWGINBHDGGIOIAILYISICJWB3J0IJOGIJG0NDMILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIMHRMDEUBGLUA2L0BM93LM5LDCISICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje5ljq3ljiwiiwgimfpzci6iciwiiwgimfscg4ioiaiiiwgimzwijogiiisicjob3n0ijogimhrmdeubglua2l0bm93lm5ldcisicjpzci6icizoteznwezos1lnmnhltqzzgytytm2mc1kodu5zwvhnthkodyilcaibmv0ijogindziiwginbhdggioiailyisicjwb3j0ijogijg0ndmilcaic2n5ijogimf1dg8ilcaic25pijogimhrmdeubglua2l0bm93lm5ldcisicj0bhmioiaidgxziiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXMDQUMJEUNJKUNDQILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC01MTE5NTI0MJQUBWNPDGVSLMNVIIWIAWQIOIJUYXNUZXQILCJUZXQIOIJ3CYISINBHDGGIOIIVBMFZBMV0L2NKBIISINBVCNQIOII4MDGWIIWICHMIOILWN5QANZHAB25LY2XPY2T2CG5RZXLZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixmdqumjeunjkundqilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc01mte5nti0mjqubwnpdgvslmnviiwiawqioijuyxnuzxqilcjuzxqioij3cyisinbhdggioiivbmfzbmv0l2nkbiisinbvcnqioii4mdgwiiwichmioilwn5qanzhab25ly2xpy2t2cg5rzxlziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOILZGDUM2YTYQTIX2LTAQDMGINIX2KFBJNQV2KFZHVCFKYH2CG5VD2XAIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioilzgdum2ytyqtix2ltaqdmginix2kfbjnqv2kfzhvcfkyh2cg5vd2xaiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIJMB3JJZTYUZ29SZHNWZWVKLM9YZYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOILZ9CSUFFVEVMRUDSQU1ATUFSQU1CQVNISV9NQVJBTUJBU0HJX01BUKFNQKFTSELFTUFSQU1CQVNISV9NQVJBTUJBU0HJIIWIAWQIOIJIMDI3ZMIYNS1MN2ZILTRLNGETOTRINS1LNZI2NZFJOGZHMJKILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIILCJWB3J0IJOINTG5NZIILCJWCYI6IKBNQVJBTUJBU0HJIPCFMLBIGI3WN4YR77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmb3jjztyuz29szhnwzwvklm9yzyisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoilz9csuffvevmrudsqu1atufsqu1cqvnisv9nqvjbtujbu0hjx01bukfnqkftselftufsqu1cqvnisv9nqvjbtujbu0hjiiwiawqioijimdi3zmiyns1mn2ziltrlngetotrins1lnzi2nzfjogzhmjkilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiiilcjwb3j0ijointg5nziilcjwcyi6ikbnqvjbtujbu0hjipcfmlbigi3wn4yr77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJOVZEUEMT2BY50B3AILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYZEYYTU4MMITYZJLMS00OTRLLWIXYWMTMTG1ZDQ0YZI5NTJMIIWIBMV0IJOIDGNWIIWICGF0ACI6IIISINBVCNQIOIIYMDKWIIWICHMIOIJAYXBWC29VBMVYINQP2KFZHTIN2YQG2KRZHNQV2LHYP9MFIPCFLYRVUI8ILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijovzeuemt2by50b3ailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiyzeyytu4mmityzjlms00otrllwixywmtmtg1zdq0yzi5ntjmiiwibmv0ijoidgnwiiwicgf0aci6iiisinbvcnqioiiymdkwiiwichmioijayxbwc29vbmvyinqp2kfzhtin2yqg2krzhnqv2lhyp9mfipcflyrvui8ilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| HTTP | 470687 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 431673 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 235 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 454424 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 466884 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5297 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 85 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6018 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27557 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7260 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
