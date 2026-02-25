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

Last Updated: 2026-02-25 14:31:37 UTC

**Total Proxies: 1794419**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| EYJHZGQIOII0NS4XMY4YMJCUMTE4IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULIGPLI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ULI4ILCJPZCI6IJHJZTY0NJYYLWY4YJGTNDK1NS1IZGYYLWE1NWI4MJFIYZRHYSISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II9LEUPXZFC1CKLQB2LOREJOV0DZM1OWTLBKMGXVWJJZAUXDSNDJBTKWYJJODMJDSTZJBLPZSWL3AWJXOWTAU0K2SW5CEWIZADVHWEFPTENKD1LXNWXIRWXRY3LJNLCXMTKILCJWB3J0IJOIODAILCJWCYI6IKLSLUBWMNJHEUFSCGHHLTI5IIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii0ns4xmy4ymjcumte4iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiuli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uligpli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4uli4ilcjpzci6ijhjzty0njyylwy4yjgtndk1ns1izgyylwe1nwi4mjfiyzrhysisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii9leupxzfc1cklqb2lorejov0dzm1owtlbkmgxvwjjzauxdsndjbtkwyjjodmjdstzjblpzswl3awjxowtau0k2sw5cewizadvhwefptenkd1lxnwxirwxry3ljnlcxmtkilcjwb3j0ijoiodailcjwcyi6iklslubwmnjheufscghhlti5iiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII1NY4XMJKUMJUUMJMILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6INLPY2H1ZW5NLM9YZYISIMLKIJOIMDNMY2M2MTGTYJKZZC02NZK2LTZHZWQTOGEZOGM5NZVKNTGXIIWIBMV0IJOID3MILCJWYXROIJOIBGLUA3Z3CYISINBVCNQIOII0NDMILCJWCYI6IUKTKDVAB25LY2XPY2T2CG5RZXLZIIWIC2N5IJOIYXV0BYISINNUASI6INLPY2H1ZW5NLM9YZYISINRSCYI6INRSCYISINR5CGUIOIIILCJ2IJOIMIJ9TROJAN | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii1ny4xmjkumjuumjmilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6inlpy2h1zw5nlm9yzyisimlkijoimdnmy2m2mtgtyjkzzc02nzk2ltzhzwqtogezogm5nzvkntgxiiwibmv0ijoid3milcjwyxroijoibglua3z3cyisinbvcnqioii0ndmilcjwcyi6iuktkdvab25ly2xpy2t2cg5rzxlziiwic2n5ijoiyxv0byisinnuasi6inlpy2h1zw5nlm9yzyisinrscyi6inrscyisinr5cguioiiilcj2ijoimij9trojan.txt |
| EYJHZGQIOII4LJIXMC43OS4YMTIILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYWEZYZMWMTGTMJG4YI00NMYZLWFMMWMTOTA0NGUXOGQ2ZTVIIIWIAW5ZZWN1CMUIOIIWIIWIBMV0IJOID3MILCJWYXROIJOIL05VDGLMX0NOYXQILCJWB3J0IJOINTUXODUILCJWCYI6IVCFH63WN4EWQEZYZWFRQ29UZMLNIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii4ljixmc43os4ymtiilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiywezyzmwmtgtmjg4yi00nmyzlwfmmwmtota0nguxogq2ztviiiwiaw5zzwn1cmuioiiwiiwibmv0ijoid3milcjwyxroijoil05vdglmx0noyxqilcjwb3j0ijointuxoduilcjwcyi6ivcfh63wn4ewqezyzwfrq29uzmlniiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXMDQUMJEUNJKUNDQILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC01MTE5NTI0MJQUBWNPDGVSLMNVIIWIAWQIOIJUYXNUZXQILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIVBMFZBMV0L2NKBIISINBVCNQIOII4MDGWIIWICHMIOIJATUFSQU1CQVNISSDWN6W2IIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixmdqumjeunjkundqilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc01mte5nti0mjqubwnpdgvslmnviiwiawqioijuyxnuzxqilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiivbmfzbmv0l2nkbiisinbvcnqioii4mdgwiiwichmioijatufsqu1cqvnissdwn6w2iiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXOTMUMTUXLJE0NI4YMZIILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIZJK1Y2I1YWUTMWIWNI00YTU3LWFIYTATMZBHZMUXMMQYM2VKIIWIBMV0IJOIDGNWIIWICGF0ACI6IIISINBVCNQIOIIXNZM1NIISINBZIJOIQEZHCMF6VJJYYXKILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixotmumtuxlje0ni4ymziilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoizjk1y2i1ywutmwiwni00ytu3lwfiytatmzbhzmuxmmqym2vkiiwibmv0ijoidgnwiiwicgf0aci6iiisinbvcnqioiixnzm1niisinbzijoiqezhcmf6vjjyyxkilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| EYJHZGQIOIIYMC4XOTMUMTUZLJE5IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIILCJPZCI6IJM5YTHJMZC0LTC2YJETNGU5MC1HYJG1LTG1Y2Q5YTQYZGVKMIISIMLUC2VJDXJLIJOIMCISIM5LDCI6INRJCCISINBHDGGIOIIILCJWB3J0IJOIMTU4MZQILCJWCYI6IK1DSS1AVJJYYXLBBHBOYS0TMTYILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiiymc4xotmumtuzlje5iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiilcjpzci6ijm5ythjmzc0ltc2yjetngu5mc1hyjg1ltg1y2q5ytqyzgvkmiisimluc2vjdxjlijoimcisim5ldci6inrjccisinbhdggioiiilcjwb3j0ijoimtu4mzqilcjwcyi6ik1dss1avjjyyxlbbhboys0tmtyilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| EYJHZGQIOIJ0Z2P1LM9YZYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIBMFZBMV0LTU3MTI5NJQ5NY5PCMFUCHJLC3MUY28ILCJPZCI6IMU4YJE1MDBILWU5ZTGTNTQ5MI04MZEYLWY0ZWFKZJDKMDC2NYISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUIIWICG9YDCI6IJGWODAILCJWCYI6IVCFM6EGVIAXMDEGQE91DGXPBMVFVNBUIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioij0z2p1lm9yzyisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoibmfzbmv0ltu3mti5njq5ny5pcmfuchjlc3muy28ilcjpzci6imu4yje1mdbilwu5ztgtntq5mi04mzeylwy0zwfkzjdkmdc2nyisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2ruiiwicg9ydci6ijgwodailcjwcyi6ivcfm6egviaxmdegqe91dgxpbmvfvnbuiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJKZC5VCGVUYWNJZXNZBM9KZS5JB20ILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM10YWXRLMDVB2DSZS5JB20ILCJPZCI6IJC1MTKZYMVMLTHKOGYTZTGYMY00MWUWLTJKZDA4M2RJMTM5OSISIM5LDCI6INRJCCISINBHDGGIOIIVQEPHDMLKBMFTYW5JCMFUL0PHDMLKLVNIQUGTS2LUZ1JLEMFQYWHSYXZPLYISINBVCNQIOII1MDIILCJWCYI6IVCFPY41N0BVBMVJBGLJA3ZWBMTLEXMILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IMH0DHAILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijkzc5vcgvuywnjzxnzbm9kzs5jb20ilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im10ywxrlmdvb2dszs5jb20ilcjpzci6ijc1mtkzymvmlthkogytztgymy00mwuwltjkzda4m2rjmtm5osisim5ldci6inrjccisinbhdggioiivqephdmlkbmftyw5jcmful0phdmlklvniqugts2luz1jlemfqywhsyxzplyisinbvcnqioii1mdiilcjwcyi6ivcfpy41n0bvbmvjbglja3zwbmtlexmilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6imh0dhailcj2ijoimij9vless.txt |
| EYJHZGQIOIJMCMVLZG9TLNZPCGDZBXRLYW0UAW5MBYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJMOTVJYJVHZS0XYJA2LTRHNTCTYWJHMC0ZMGFMZTEYZDIZZWQILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJE3MZU2IIWICHMIOILWN4E68J+HUEFSBOKBTSB8IEBCAWDTBW9RZV9DB25MAWCILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmcmvlzg9tlnzpcgdzbxrlyw0uaw5mbyisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijmotvjyjvhzs0xyja2ltrhntctywjhmc0zmgfmzteyzdizzwqilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ije3mzu2iiwichmioilwn4e68j+huefsbokbtsb8iebcawdtbw9rzv9db25mawcilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| HTTP | 450506 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 415452 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 6 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 177 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 3 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 436522 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 448137 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5232 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 92 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 4468 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 6 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 27945 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 5843 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
