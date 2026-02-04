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

Last Updated: 2026-02-04 19:57:28 UTC

**Total Proxies: 1859890**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYDHZGQNOIANMTCYLJY3LJIWNC44NCCSICDHAWQNOIANMCCSICDHBHBUJZOGJYCSICDMCCC6ICCNLCANAG9ZDCC6ICDUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYCSICDPZCC6ICDUYXNUZXQNLCANAW5ZZWN1CMUNOIANMCCSICDUZXQNOIAND3MNLCANCGF0ACC6ICCVBMFZBMV0L2NKBICSICDWB3J0JZOGJZGWODANLCANCHMNOIANQFNQRUVEU19WUE4XLFCFQBGNLCANC2N5JZOGJ2F1DG8NLCANC25PJZOGJYCSICD0BHMNOIANJYWGJ3R5CGUNOIANLS0TJYWGJ3YNOIANMID9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eydhzgqnoianmtcyljy3ljiwnc44nccsicdhawqnoianmccsicdhbhbujzogjycsicdmccc6iccnlcanag9zdcc6icduyxnuzxqtntexotuyndi0lm1jaxrlbc5jbycsicdpzcc6icduyxnuzxqnlcanaw5zzwn1cmunoianmccsicduzxqnoiand3mnlcancgf0acc6iccvbmfzbmv0l2nkbicsicdwb3j0jzogjzgwodanlcanchmnoianqfnqruveu19wue4xlfcfqbgnlcanc2n5jzogj2f1dg8nlcanc25pjzogjycsicd0bhmnoianjywgj3r5cgunoianls0tjywgj3ynoianmid9vless.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIMPHAGZRAMHHLMNMZCISICJWB3J0IJOGIJQ0MYISICJPZCI6ICI5NTBKYJZHYS00OTI2LTQ2MTYTODE2ZS1LYZAZMTJKY2I4N2IILCAIYWLKIJOGIJAILCAIC2N5IJOGIMF1DG8ILCAIBMV0IJOGINDZIIWGINR5CGUIOIAIBM9UZSISICJOB3N0IJOGIIISICJWYXROIJOGII9SAW5RD3MILCAIDGXZIJOGINRSCYISICJZBMKIOIAIIIWGIMFSCG4IOIAIIIWGIMZWIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogimphagzramhhlmnmzcisicjwb3j0ijogijq0myisicjpzci6ici5ntbkyjzhys00oti2ltq2mtytode2zs1lyzazmtjky2i4n2iilcaiywlkijogijailcaic2n5ijogimf1dg8ilcaibmv0ijogindziiwginr5cguioiaibm9uzsisicjob3n0ijogiiisicjwyxroijogii9saw5rd3milcaidgxzijoginrscyisicjzbmkioiaiiiwgimfscg4ioiaiiiwgimzwijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIMTA0LJE2LJYXLJGILCAIYWLKIJOGIJAILCAIYWXWBII6ICIILCAIZNAIOIAIIIWGIMHVC3QIOIAIDM1LC3MUDGF4YXI3MTA1NC53B3JRZXJZLMRLDIISICJPZCI6ICI0NDFKYTM0MI1JZTKWLTQ0MWUTYMZMOS1KMMNLYJU1ZTY4Y2EILCAIBMV0IJOGINDZIIWGINBHDGGIOIAIL2L2AWRLB3MUC2JZL2XPBMT3CYISICJWB3J0IJOGIJIWODYILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIIISICJ0BHMIOIAIIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje2ljyxljgilcaiywlkijogijailcaiywxwbii6iciilcaiznaioiaiiiwgimhvc3qioiaidm1lc3mudgf4yxi3mta1nc53b3jrzxjzlmrldiisicjpzci6ici0ndfkytm0mi1jztkwltq0mwutymzmos1kmmnlyju1zty4y2eilcaibmv0ijogindziiwginbhdggioiail2l2awrlb3muc2jzl2xpbmt3cyisicjwb3j0ijogijiwodyilcaic2n5ijogimf1dg8ilcaic25pijogiiisicj0bhmioiaiiiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXMDQUMJEUNJKUNDQILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC01MTE5NTI0MJQUBWNPDGVSLMNVIIWIAWQIOIJUYXNUZXQILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIVBMFZBMV0L2NKBIISINBVCNQIOII4MDGWIIWICHMIOIJATUFSQU1CQVNISSDWN6SNIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixmdqumjeunjkundqilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc01mte5nti0mjqubwnpdgvslmnviiwiawqioijuyxnuzxqilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiivbmfzbmv0l2nkbiisinbvcnqioii4mdgwiiwichmioijatufsqu1cqvnissdwn6sniiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZMUMJQ5LJIWOS4XNDYILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIMZKZNWMYZGMTZGJIMC00M2Y3LWIZNJCTZMU4OWFIZTG3ZMRMIIWIBMV0IJOID3MILCJWYXROIJOILYISINBVCNQIOIIYMDA4NIISINBZIJOIQGFWCHNVB25LCIDAQDIN2YBYP9MEINIQ2YTAR9IX2KFZHSDWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnzmumjq5ljiwos4xndyilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoimzkznwmyzgmtzgjimc00m2y3lwiznjctzmu4owfiztg3zmrmiiwibmv0ijoid3milcjwyxroijoilyisinbvcnqioiiymda4niisinbzijoiqgfwchnvb25lcidaqdin2ybyp9meiniq2ytar9ix2kfzhsdwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOILZGDUM2YTYQTIX2LTAQDMGINIX2KFBJNQV2KFZHVCFKYH2CG5VD2XAIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioilzgdum2ytyqtix2ltaqdmginix2kfbjnqv2kfzhvcfkyh2cg5vd2xaiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIJHCNNHBGFULMFYC2FSYW52MY5ZYNMILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IMFYC2FSYW4UYXJZYWXHBNYZLNNICYISIMLKIJOIYZIXOWIZM2YTZJNJMY00ZJCWLTLLMTITNZLINDYXOGEYMTBLIIWIBMV0IJOID3MILCJWYXROIJOILYISINBVCNQIOIIYMDK1IIWICHMIOIJDB25MAWDWMLJHEU5HIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9TROJAN | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijhcnnhbgfulmfyc2fsyw52my5zynmilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6imfyc2fsyw4uyxjzywxhbnyzlnnicyisimlkijoiyzixowizm2ytzjnjmy00zjcwltllmtitnzlindyxogeymtbliiwibmv0ijoid3milcjwyxroijoilyisinbvcnqioiiymdk1iiwichmioijdb25mawdwmljheu5hiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9trojan.txt |
| EYJWB3J0IJOIMJAYMCISINBHDGGIOIJCLYISIMFKZCI6IMNPCC5LCNRLYMF0Z29VC3RHCI5PCIISINNJESI6IMF1DG8ILCJUZXQIOIJ0Y3AILCJWCYI6IIU0MEZSRUVFVLBOMDIILCJPZCI6IJA3NJKYOGY5LTHKZJGTNGE3MS05ZTFJLWM3NTY1OGZLMZE0MCISINR5CGUIOIJODHRWIIWIAG9ZDCI6IIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjwb3j0ijoimjaymcisinbhdggioijclyisimfkzci6imnpcc5lcnrlymf0z29vc3rhci5pciisinnjesi6imf1dg8ilcjuzxqioij0y3ailcjwcyi6iiu0mezsruvfvlbomdiilcjpzci6ija3njkyogy5lthkzjgtnge3ms05ztfjlwm3nty1ogzlmze0mcisinr5cguioijodhrwiiwiag9zdci6iij9ss.txt |
| HTTP | 468278 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 428871 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 242 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 451848 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 463963 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5326 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 80 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6095 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27849 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7300 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
