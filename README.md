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

Last Updated: 2026-02-08 07:56:23 UTC

**Total Proxies: 1796755**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYJHZGQIOIAIMTA0LJE5LJQ4LJE4IIWGIMFPZCI6IDASICJOB3N0IJOGIMHRMDEUBGLUA2L0BM93LM5LDCISICJPZCI6ICIZOTEZNWEZOS1LNMNHLTQZZGYTYTM2MC1KODU5ZWVHNTHKODYILCAIBMV0IJOGINDZIIWGINBHDGGIOIAILYISICJWB3J0IJOGODQ0MYWGINRSCYI6ICJ0BHMILCAIDHLWZSI6ICJHDXRVIIWGINNLY3VYAXR5IJOGIMF1DG8ILCAIC2TPCC1JZXJ0LXZLCMLMESI6IGZHBHNLLCAIC25PIJOGIMHRMDEUBGLUA2L0BM93LM5LDCISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje5ljq4lje4iiwgimfpzci6idasicjob3n0ijogimhrmdeubglua2l0bm93lm5ldcisicjpzci6icizoteznwezos1lnmnhltqzzgytytm2mc1kodu5zwvhnthkodyilcaibmv0ijogindziiwginbhdggioiailyisicjwb3j0ijogodq0mywginrscyi6icj0bhmilcaidhlwzsi6icjhdxrviiwginnly3vyaxr5ijogimf1dg8ilcaic2tpcc1jzxj0lxzlcmlmesi6igzhbhnllcaic25pijogimhrmdeubglua2l0bm93lm5ldcisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII0NS4XNDEUMTQ4LJE0MYISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIYM1PLMLYIIWIAWQIOIJLNZIWZDJINI04MGRKLTQ2NJQTYJY0ZS02Y2M3ODRIY2UZMJKILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIVIIWICG9YDCI6IJUWNTKILCJWCYI6IVCFH7NWN4E3QEZYZWFRQ29UZMLNIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii0ns4xndeumtq4lje0myisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiym1plmlyiiwiawqioijlnziwzdjini04mgrkltq2njqtyjy0zs02y2m3odriy2uzmjkilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiiviiwicg9ydci6ijuwntkilcjwcyi6ivcfh7nwn4e3qezyzwfrq29uzmlniiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII4LJIXMC43OS4YMTIILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYWEZYZMWMTGTMJG4YI00NMYZLWFMMWMTOTA0NGUXOGQ2ZTVIIIWIAW5ZZWN1CMUIOIIWIIWIBMV0IJOID3MILCJWYXROIJOIL05VDGLMX0NOYXQILCJWB3J0IJOINTUXODUILCJWCYI6IVCFH63WN4EWQEZYZWFRQ29UZMLNIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii4ljixmc43os4ymtiilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiywezyzmwmtgtmjg4yi00nmyzlwfmmwmtota0nguxogq2ztviiiwiaw5zzwn1cmuioiiwiiwibmv0ijoid3milcjwyxroijoil05vdglmx0noyxqilcjwb3j0ijointuxoduilcjwcyi6ivcfh63wn4ewqezyzwfrq29uzmlniiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOII6OMZMZMY6YWM0MDO5YMQXIIWIYWLKIJOIMCISIMFSCG4IOIJOMIISIMZWIJOIY2HYB21LIIWIAG9ZDCI6IMJLZHJPZC5KZW5PEMHVC3RPBMCUBWUILCJPZCI6IMZMZWNLMME5LTAYOTYTNDZHOS04ZGI4LTC0MMQYOWQYNDBMZIISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6IKLTD3BZVLI4U2P4WGNVWKVVELZMTLVSVFVDOGXWMJLEWFNNC0TIMVNOMGCXSLZWREHVMWNXAWDLQUM4UVJSDE1DATG2QUJ3NEPWMTRIVK1UIIWICG9YDCI6IJQ0MYISINBZIJOIQGLJDJJYYXKILCJZY3KIOIJHDXRVIIWIC25PIJOIYMVKCMLKLMRLBML6AG9ZDGLUZY5TZSISINRSCYI6INRSCYISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii6omzmzmy6ywm0mdo5ymqxiiwiywlkijoimcisimfscg4ioijomiisimzwijoiy2hyb21liiwiag9zdci6imjlzhjpzc5kzw5pemhvc3rpbmcubwuilcjpzci6imzmzwnlmme5ltayotytndzhos04zgi4ltc0mmqyowqyndbmziisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ikltd3bzvli4u2p4wgnvwkvvelzmtlvsvfvdogxwmjlewfnnc0timvnomgcxslzwrehvmwnxawdlqum4uvjsde1datg2quj3nepwmtrivk1uiiwicg9ydci6ijq0myisinbzijoiqgljdjjyyxkilcjzy3kioijhdxrviiwic25pijoiymvkcmlklmrlbml6ag9zdgluzy5tzsisinrscyi6inrscyisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZMUMJQ5LJIWOS4XNDYILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIMZKZNWMYZGMTZGJIMC00M2Y3LWIZNJCTZMU4OWFIZTG3ZMRMIIWIBMV0IJOID3MILCJWYXROIJOILYISINBVCNQIOIIYMDA4NIISINBZIJOIQGFWCHNVB25LCIDAQDIN2YBYP9MEINIQ2YTAR9IX2KFZHSDWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnzmumjq5ljiwos4xndyilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoimzkznwmyzgmtzgjimc00m2y3lwiznjctzmu4owfiztg3zmrmiiwibmv0ijoid3milcjwyxroijoilyisinbvcnqioiiymda4niisinbzijoiqgfwchnvb25lcidaqdin2ybyp9meiniq2ytar9ix2kfzhsdwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOILZGDUM2YTYQTIX2LTAQDMGINIX2KFBJNQV2KFZHVCFKYH2CG5VD2XAIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioilzgdum2ytyqtix2ltaqdmginix2kfbjnqv2kfzhvcfkyh2cg5vd2xaiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOIJJUI1AVJJYYXLBBHBOYS0ZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioijjui1avjjyyxlbbhboys0ziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIIYMC4XOTMUMTUZLJE5IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIILCJPZCI6IJM5YTHJMZC0LTC2YJETNGU5MC1HYJG1LTG1Y2Q5YTQYZGVKMIISIMLUC2VJDXJLIJOIMCISIM5LDCI6INRJCCISINBHDGGIOIIILCJWB3J0IJOIMTU4MZQILCJWCYI6IKLSLUBWMNJHEUFSCGHHLTEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiiymc4xotmumtuzlje5iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiilcjpzci6ijm5ythjmzc0ltc2yjetngu5mc1hyjg1ltg1y2q5ytqyzgvkmiisimluc2vjdxjlijoimcisim5ldci6inrjccisinbhdggioiiilcjwb3j0ijoimtu4mzqilcjwcyi6iklslubwmnjheufscghhlteilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| EYJHZGQIOIJ0CJETC21HCNQUYWRLBHBPBMCUY29TIIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIILCJPZCI6IJQZZGNKY2UXLTNJZWETNDE5MY1IYZHKLTKWYJKYMDCXZDC3OSISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6IIISINBVCNQIOII4MCISINBZIJOIQEZORVRQUK8G8J+HUFCFH7CGVHVYA2V5IIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioij0cjetc21hcnquywrlbhbpbmcuy29tiiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiilcjpzci6ijqzzgnky2uxltnjzwetnde5my1iyzhkltkwyjkymdcxzdc3osisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6iiisinbvcnqioii4mcisinbzijoiqezorvrquk8g8j+hufcfh7cgvhvya2v5iiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJKAWDPDGFSB2NLYW4UY29TIIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTCXMJK5NJY3LNJHAGF2YXJKMZY1LMNVIIWIAWQIOIJUYXNUZXQILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIVTKFTTKVUL2NKBIISINBVCNQIOII4MDGWIIWICHMIOIJARK5FVFBSTYB84OCIINIQ2YTAR9IX2KFZHSDIMJXWN5KZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijkawdpdgfsb2nlyw4uy29tiiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntcxmjk5njy3lnjhagf2yxjkmzy1lmnviiwiawqioijuyxnuzxqilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiivtkfttkvul2nkbiisinbvcnqioii4mdgwiiwichmioijark5fvfbstyb84ociiniq2ytar9ix2kfzhsdimjxwn5kziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJKAWDPDGFSB2NLYW4UY29TIIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTCXMJK5NJY3LNJHAGF2YXJKMZY1LMNVIIWIAWQIOIJUYXNUZXQILCJUZXQIOIJ3CYISINBHDGGIOIIVTKFTTKVUL2NKBJ9LZFX1MDAZZDI1NJAILCJWB3J0IJOIODA4MCISINBZIJOI4PIU77IPMJLAB25LY2XPY2T2CG5RZXLZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijkawdpdgfsb2nlyw4uy29tiiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntcxmjk5njy3lnjhagf2yxjkmzy1lmnviiwiawqioijuyxnuzxqilcjuzxqioij3cyisinbhdggioiivtkfttkvul2nkbj9lzfx1mdazzdi1njailcjwb3j0ijoioda4mcisinbzijoi4piu77ipmjlab25ly2xpy2t2cg5rzxlziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9vless.txt |
| EYJHZGQIOIJMYXJ6YWQUDMLWZ3NTDGVHBS5PBMZVIIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJ6DWXHLMLYIIWIAWQIOII3ZJGYNTQ0NC00OWRKLTQXNGITY2RJMI1HYZY2NDNLOTEZNTAILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ0Y3AILCJWYXROIJOILYISINBVCNQIOIIZMZK1MYISINBZIJOISVITQFYYCMF5QWXWAGETMTEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IMH0DHAILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmyxj6ywqudmlwz3ntdgvhbs5pbmzviiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioij6dwxhlmlyiiwiawqioii3zjgyntq0nc00owrkltqxngity2rjmi1hyzy2ndnlotezntailcjpbnnly3vyzsi6ijailcjuzxqioij0y3ailcjwyxroijoilyisinbvcnqioiizmzk1myisinbzijoisvitqfyycmf5qwxwagetmteilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6imh0dhailcj2ijoimij9vless.txt |
| EYJHZGQIOIJZZW91BDAZLNPNAM9RLMNVBSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIC2VVDWWWMY56Z2PVAY5JB20ILCJPZCI6IJCYYTBKYWM0LTK2ODKTNGE1NY1IMTY0LTVJNJVIZME5NDC3MIISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II8ILCJWB3J0IJOINDQZIIWICHMIOIJAAWN2MNJHESISINNJESI6IMF1DG8ILCJZBMKIOIJZZW91BDAZLNPNAM9RLMNVBSISINRSCYI6INRSCYISINR5CGUIOIITLS0ILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijzzw91bdazlnpnam9rlmnvbsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoic2vvdwwwmy56z2pvay5jb20ilcjpzci6ijcyytbkywm0ltk2odktnge1ny1imty0ltvjnjvizme5ndc3miisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii8ilcjwb3j0ijoindqziiwichmioijaawn2mnjhesisinnjesi6imf1dg8ilcjzbmkioijzzw91bdazlnpnam9rlmnvbsisinrscyi6inrscyisinr5cguioiitls0ilcj2ijoimij9ss.txt |
| HTTP | 450568 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 414838 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 229 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 436365 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 447341 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5341 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 80 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 5964 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 28619 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7366 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
