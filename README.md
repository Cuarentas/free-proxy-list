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

Last Updated: 2026-02-01 16:27:39 UTC

**Total Proxies: 1826496**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIJE3MI42NC4XNZUUODGILCAICG9YDCI6ICIYMDG2IIWGINR5CGUIOIAIBM9UZSISICJPZCI6ICJLOWUZY2MXMY1KYJQ4LTRJYZETOGMYNC03NJI2NDM5YTUZMZKILCAIYWLKIJOGIJAILCAIBMV0IJOGINDZIIWGINBHDGGIOIAIZ2L0AHVILMNVBS9BBHZPBJK5OTKILCAIAG9ZDCI6ICJPCDEUMTQ1NZIZMC54EXOILCAIDGXZIJOGIIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogije3mi42nc4xnzuuodgilcaicg9ydci6iciymdg2iiwginr5cguioiaibm9uzsisicjpzci6icjlowuzy2mxmy1kyjq4ltrjyzetogmync03nji2ndm5ytuzmzkilcaiywlkijogijailcaibmv0ijogindziiwginbhdggioiaiz2l0ahvilmnvbs9bbhzpbjk5otkilcaiag9zdci6icjpcdeumtq1nzizmc54exoilcaidgxzijogiij9vless.txt |
| EYJ2IJOGIJIILCAIYWRKIJOGIJEWNC4XOS41MS4YMZIILCAICG9YDCI6ICIYMDG2IIWGIMLKIJOGIJI5ZWVIYJYWLWIYN2ITNGE5ZC1IYME1LTK0NZC2M2Q5MJA1ZSISICJHAWQIOIAIMCISICJZY3KIOIAIYXV0BYISICJUZXQIOIAID3MILCAIDHLWZSI6ICJUB25LIIWGIMHVC3QIOIAIAXAWMDUUZHRRDTQ3LNH5EIISICJWYXROIJOGIMDPDGH1YI5JB20VQWX2AW45OTK5IIWGINRSCYI6ICIILCAIC25PIJOGIIISICJHBHBUIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9TROJAN | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaiywrkijogijewnc4xos41ms4ymziilcaicg9ydci6iciymdg2iiwgimlkijogiji5zwviyjywlwiyn2itnge5zc1iyme1ltk0nzc2m2q5mja1zsisicjhawqioiaimcisicjzy3kioiaiyxv0byisicjuzxqioiaid3milcaidhlwzsi6icjub25liiwgimhvc3qioiaiaxawmduuzhrrdtq3lnh5eiisicjwyxroijogimdpdgh1yi5jb20vqwx2aw45otk5iiwginrscyi6iciilcaic25pijogiiisicjhbhbuijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9trojan.txt |
| EYJHZGQIOIAIMTUXLJEWMS4XOTMUNTCILCAIYWLKIJOGIJAILCAIYWXWBII6ICIILCAIZNAIOIAIIIWGIMHVC3QIOIAIRGJKAMHPDZCYZWJZDTI3MMHZNTE5AI5JB20ILCAIAWQIOIAIZDY0YWJKYJCTYWVLYS00NZHJLTGXOTCTYZMYMTU5ZJQ2MGMWIIWGIM5LDCI6ICJ3CYISICJWYXROIJOGINDZLZ9LZD0YMDQ4IIWGINBVCNQIOIAIODAILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIIISICJ0BHMIOIAIIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimtuxljewms4xotmuntcilcaiywlkijogijailcaiywxwbii6iciilcaiznaioiaiiiwgimhvc3qioiairgjkamhpdzcyzwjzdti3mmhznte5ai5jb20ilcaiawqioiaizdy0ywjkyjctywvlys00nzhjltgxotctyzmymtu5zjq2mgmwiiwgim5ldci6icj3cyisicjwyxroijogindzlz9lzd0ymdq4iiwginbvcnqioiaiodailcaic2n5ijogimf1dg8ilcaic25pijogiiisicj0bhmioiaiiiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9ss.txt |
| EYJHZGQIOIAINJYUODEUMJQ3LJI0NIISICJHAWQIOIAIMCISICJHBHBUIJOGIIISICJMCCI6ICIILCAIAG9ZDCI6ICIXMJCUMC4WLJEUXHU1OTJHXHU3YTDHXHU1YJC4XHU1NGUXLMPCDTA0M2VCDTA0NDFCDTA0M2NCDTA0MZHCDTA0NDDCDTA0MZVCDTA0NDFCDTA0M2FCDTA0MZHCDTA0MZLCDTA0M2FCDTA0MZBCDTA0MZRCDTA0MZVCDTA0NDIUC3BHY2VJYWRLDC5CDTVIODLCDTK3NWNCDTC2ODRCDTU3MZBCDTY1YJLCDTDIMMNCDTU5MJLKYXKWBMUUD29UA2FJYXBPDGFUBY5IDXP6LIISICJPZCI6ICIYOGY4ZDUXYS0WZTC1LTRMYZMTYTM2ZS0WM2JMNGU0ZDA5MTAILCAIBMV0IJOGINDZIIWGINBHDGGIOIAIL3ZTZXNZIIWGINBVCNQIOIAIODAILCAIC2N5IJOGIM5VBMUILCAIC25PIJOGIIISICJ0BHMIOIAIIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiainjyuodeumjq3lji0niisicjhawqioiaimcisicjhbhbuijogiiisicjmcci6iciilcaiag9zdci6icixmjcumc4wljeuxhu1otjhxhu3ytdhxhu1yjc4xhu1nguxlmpcdta0m2vcdta0ndfcdta0m2ncdta0mzhcdta0nddcdta0mzvcdta0ndfcdta0m2fcdta0mzhcdta0mzlcdta0m2fcdta0mzbcdta0mzrcdta0mzvcdta0ndiuc3bhy2vjywrldc5cdtviodlcdtk3nwncdtc2odrcdtu3mzbcdty1yjlcdtdimmncdtu5mjlkyxkwbmuud29ua2fjyxbpdgfuby5idxp6liisicjpzci6iciyogy4zduxys0wztc1ltrmyzmtytm2zs0wm2jmngu0zda5mtailcaibmv0ijogindziiwginbhdggioiail3ztzxnziiwginbvcnqioiaiodailcaic2n5ijogim5vbmuilcaic25pijogiiisicj0bhmioiaiiiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOIAIY2FRZS5JYXBLBGXHCMUUY29TIIWGIMFPZCI6ICIWIIWGIMFSCG4IOIAIIIWGIMZWIJOGIIISICJOB3N0IJOGIMNHA2UUY2FWZWXSYXJLLMNVBSISICJPZCI6ICIWM2ZJYZYXOC1IOTNKLTY3OTYTNMFLZC04YTM4YZK3NWQ1ODEILCAIBMV0IJOGINDZIIWGINBHDGGIOIAIL2XPBMT2D3MILCAICG9YDCI6ICI0NDMILCAIC2N5IJOGIMF1DG8ILCAIC25PIJOGIMNHA2UUY2FWZWXSYXJLLMNVBSISICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIIIWGINYIOIAIMIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaiy2frzs5jyxblbgxhcmuuy29tiiwgimfpzci6iciwiiwgimfscg4ioiaiiiwgimzwijogiiisicjob3n0ijogimnha2uuy2fwzwxsyxjllmnvbsisicjpzci6iciwm2zjyzyxoc1iotnklty3otytnmflzc04ytm4yzk3nwq1odeilcaibmv0ijogindziiwginbhdggioiail2xpbmt2d3milcaicg9ydci6ici0ndmilcaic2n5ijogimf1dg8ilcaic25pijogimnha2uuy2fwzwxsyxjllmnvbsisicj0bhmioiaidgxziiwginr5cguioiaiiiwginyioiaimiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXMDQUMJEUNJKUNDQILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC01MTE5NTI0MJQUBWNPDGVSLMNVIIWIAWQIOIJUYXNUZXQILCJUZXQIOIJ3CYISINBHDGGIOIIVBMFZBMV0L2NKBIISINBVCNQIOII4MDGWIIWICHMIOILWN5QANZHAB25LY2XPY2T2CG5RZXLZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixmdqumjeunjkundqilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc01mte5nti0mjqubwnpdgvslmnviiwiawqioijuyxnuzxqilcjuzxqioij3cyisinbhdggioiivbmfzbmv0l2nkbiisinbvcnqioii4mdgwiiwichmioilwn5qanzhab25ly2xpy2t2cg5rzxlziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOILZGDUM2YTYQTIX2LTAQDMGINIX2KFBJNQV2KFZHVCFKYH2CG5VD2XAIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioilzgdum2ytyqtix2ltaqdmginix2kfbjnqv2kfzhvcfkyh2cg5vd2xaiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIJMB3JJZTYUZ29SZHNWZWVKLM9YZYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOILZ9CSUFFVEVMRUDSQU1ATUFSQU1CQVNISV9NQVJBTUJBU0HJX01BUKFNQKFTSELFTUFSQU1CQVNISV9NQVJBTUJBU0HJIIWIAWQIOIJIMDI3ZMIYNS1MN2ZILTRLNGETOTRINS1LNZI2NZFJOGZHMJKILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIILCJWB3J0IJOINTG5NZIILCJWCYI6IKBNQVJBTUJBU0HJIPCFMLBIGI3WN4YR77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmb3jjztyuz29szhnwzwvklm9yzyisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoilz9csuffvevmrudsqu1atufsqu1cqvnisv9nqvjbtujbu0hjx01bukfnqkftselftufsqu1cqvnisv9nqvjbtujbu0hjiiwiawqioijimdi3zmiyns1mn2ziltrlngetotrins1lnzi2nzfjogzhmjkilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiiilcjwb3j0ijointg5nziilcjwcyi6ikbnqvjbtujbu0hjipcfmlbigi3wn4yr77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJOVZEUEMT2BY50B3AILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYZEYYTU4MMITYZJLMS00OTRLLWIXYWMTMTG1ZDQ0YZI5NTJMIIWIBMV0IJOIDGNWIIWICGF0ACI6IIISINBVCNQIOIIYMDKWIIWICHMIOIJAYXBWC29VBMVYINQP2KFZHTIN2YQG2KRZHNQV2LHYP9MFIPCFLYRVUI8ILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijovzeuemt2by50b3ailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiyzeyytu4mmityzjlms00otrllwixywmtmtg1zdq0yzi5ntjmiiwibmv0ijoidgnwiiwicgf0aci6iiisinbvcnqioiiymdkwiiwichmioijayxbwc29vbmvyinqp2kfzhtin2yqg2krzhnqv2lhyp9mfipcflyrvui8ilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| HTTP | 459105 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 420242 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 234 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 444285 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 456343 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5305 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 81 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6066 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27575 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7220 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
