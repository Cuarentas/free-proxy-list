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

Last Updated: 2026-02-11 16:00:38 UTC

**Total Proxies: 1801857**

Click on your preferred proxy type to get the latest list. These links always point to the most recently updated proxy files.

| Protocol | Count | Download |
|----------|-------|----------|
| ANYTLS | 24 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/anytls.txt |
| EYDHZGQNOIANMTQWLJI0OC4XOTEUNJKNLCANYWLKJZOGJZANLCANYWXWBIC6ICCNLCANZNANOIANJYWGJ2HVC3QNOIANCGWZAGN5B3VYLW5HBWUUZ2XVYMFSLNNZBC5MYXN0BHKUBMV0JYWGJ2LKJZOGJ2FHMJKZMMMXLTJHMJKTNDLINY1HZWVHLTBMODAWYMZKMDDKZSCSICDPBNNLY3VYZSC6ICCWJYWGJ25LDCC6ICD4AHR0CCCSICDWYXROJZOGJY8NLCANCG9YDCC6ICC4MCCSICDWCYC6ICDAU1BFRURTX1ZQTJETXFUWMDAXZMFJNICSICDZY3KNOIANYXV0BYCSICDZBMKNOIANJYWGJ3RSCYC6ICCNLCANDHLWZSC6ICDHDXRVJYWGJ3YNOIANMID9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eydhzgqnoianmtqwlji0oc4xoteunjknlcanywlkjzogjzanlcanywxwbic6iccnlcanznanoianjywgj2hvc3qnoiancgwzagn5b3vylw5hbwuuz2xvymfslnnzbc5myxn0bhkubmv0jywgj2lkjzogj2fhmjkzmmmxltjhmjktndliny1hzwvhltbmodawymzkmddkzscsicdpbnnly3vyzsc6iccwjywgj25ldcc6icd4ahr0cccsicdwyxrojzogjy8nlcancg9ydcc6icc4mccsicdwcyc6icdau1bfrurtx1zqtjetxfuwmdaxzmfjnicsicdzy3knoianyxv0bycsicdzbmknoianjywgj3rscyc6iccnlcandhlwzsc6icdhdxrvjywgj3ynoianmid9vless.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIJE4OC4XMTQUOTYUMJIXIIWGINBVCNQIOIAIODAILCAIDHLWZSI6ICJUB25LIIWGIMLKIJOGIJLHYZK0N2FHLWRLODYTNDFJMY05YTYWLTRJMDYXYZDJOTVMMCISICJHAWQIOIAIMCISICJUZXQIOIAID3MILCAICGF0ACI6ICIVDM1LC3MILCAIAG9ZDCI6ICJKBDMUCGXVDC5JXHUWNDQ2XHUWNDM1XHUWNDNKXHUWNDMWXHUWNDQWXHUWNDM4XHUWNDM5LLX1NTI4N1X1NJBJNVX1MDQZM1X1MDQZZVX1MDQZYLX1MDQZZVX1MDQZMJBCDTA0NDBCDTA0MZVCDTA0MZCUZMLYM2JYYW5KLLX1NZE3ZFX1NTJKNVX1ODAWNVX1OGZMZFX1OTAXMFX1OTZMN1X1NJA2OS5CDTA0M2ZCDTA0M2VCDTA0MZNCDTA0M2VCDTA0M2RCDTA0MZVCDTA0MZDCDTA0MZBWXHUWNDM1XHUWNDM5XHUWNDNKLNDVBMTHY2FWAXRHBM8UYNV6EI4ILCAIDGXZIJOGIIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogije4oc4xmtquotyumjixiiwginbvcnqioiaiodailcaidhlwzsi6icjub25liiwgimlkijogijlhyzk0n2fhlwrlodytndfjmy05ytywltrjmdyxyzdjotvmmcisicjhawqioiaimcisicjuzxqioiaid3milcaicgf0aci6icivdm1lc3milcaiag9zdci6icjkbdmucgxvdc5jxhuwndq2xhuwndm1xhuwndnkxhuwndmwxhuwndqwxhuwndm4xhuwndm5llx1nti4n1x1njbjnvx1mdqzm1x1mdqzzvx1mdqzylx1mdqzzvx1mdqzmjbcdta0ndbcdta0mzvcdta0mzcuzmlym2jyyw5kllx1nze3zfx1ntjknvx1odawnvx1ogzmzfx1otaxmfx1otzmn1x1nja2os5cdta0m2zcdta0m2vcdta0mzncdta0m2vcdta0m2rcdta0mzvcdta0mzdcdta0mzbwxhuwndm1xhuwndm5xhuwndnklndvbmthy2fwaxrhbm8uynv6ei4ilcaidgxzijogiij9vless.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGIJEYOS4XNTAUNJEUMTCWIIWGINBVCNQIOIAIMJK0OTMILCAIDHLWZSI6ICJUB25LIIWGIMLKIJOGIMFJMGQWMDC2LTKZZDITNDHHZC1IYTZLLWVHNWM4ZDDIMDEZMIISICJHAWQIOIAIMCISICJUZXQIOIAID3MILCAICGF0ACI6ICIVIIWGIMHVC3QIOIAIMTI5LJE1MC42MS4XNZAILCAIDGXZIJOGIIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijogijeyos4xntaunjeumtcwiiwginbvcnqioiaimjk0otmilcaidhlwzsi6icjub25liiwgimlkijogimfjmgqwmdc2ltkzzditndhhzc1iytzllwvhnwm4zddimdezmiisicjhawqioiaimcisicjuzxqioiaid3milcaicgf0aci6iciviiwgimhvc3qioiaimti5lje1mc42ms4xnzailcaidgxzijogiij9ss.txt |
| EYJ2IJOGIJIILCAICHMIOIAIQEHVCGVFTMV0LWPVAW4TDXMTB24TVGVSZWDYYW0ILCAIYWRKIJOGINN1NC5JAGFVEG4UDG9WIIWGINBVCNQIOIAIODAILCAIDHLWZSI6ICJUB25LIIWGIMLKIJOGIJLLNGE3MJY4LTRJNJYTNDLKOS1INMZILTU5ZTMZYZHJN2M1OSISICJHAWQIOIAIMCISICJUZXQIOIAID3MILCAICGF0ACI6ICIVIIWGIMHVC3QIOIAIC3U0LMNOYW94BI50B3AILCAIDGXZIJOGIIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyj2ijogijiilcaichmioiaiqehvcgvftmv0lwpvaw4tdxmtb24tvgvszwdyyw0ilcaiywrkijoginn1nc5jagfveg4udg9wiiwginbvcnqioiaiodailcaidhlwzsi6icjub25liiwgimlkijogijllnge3mjy4ltrjnjytndlkos1inmziltu5ztmzyzhjn2m1osisicjhawqioiaimcisicjuzxqioiaid3milcaicgf0aci6iciviiwgimhvc3qioiaic3u0lmnoyw94bi50b3ailcaidgxzijogiij9vless.txt |
| EYJHZGQIOIAIMTA0LJE5LJQ3LJIYMYISICJHAWQIOIAWLCAIAG9ZDCI6ICJOAZAXLMXPBMTPDG5VDY5UZXQILCAIAWQIOIAIMZKXMZVHMZKTZTZJYS00M2RMLWEZNJATZDG1OWVLYTU4ZDG2IIWGIM5LDCI6ICJ3CYISICJWYXROIJOGII8ILCAICG9YDCI6IDG0NDMSICJ0BHMIOIAIDGXZIIWGINR5CGUIOIAIYXV0BYISICJZZWN1CML0ESI6ICJHDXRVIIWGINNRAXATY2VYDC12ZXJPZNKIOIB0CNVLLCAIC25PIJOGIIISICJWCYI6ICJASG9WZV9OZXQTAM9PBI11CY1VBI1UZWXLZ3JHBSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiaimta0lje5ljq3ljiymyisicjhawqioiawlcaiag9zdci6icjoazaxlmxpbmtpdg5vdy5uzxqilcaiawqioiaimzkxmzvhmzktztzjys00m2rmlweznjatzdg1owvlytu4zdg2iiwgim5ldci6icj3cyisicjwyxroijogii8ilcaicg9ydci6idg0ndmsicj0bhmioiaidgxziiwginr5cguioiaiyxv0byisicjzzwn1cml0esi6icjhdxrviiwginnraxaty2vydc12zxjpznkioib0cnvllcaic25pijogiiisicjwcyi6icjasg9wzv9ozxqtam9pbi11cy1vbi1uzwxlz3jhbsj9vless.txt |
| EYJHZGQIOII4LJIXMC43OS4YMTIILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IIISIMLKIJOIYWEZYZMWMTGTMJG4YI00NMYZLWFMMWMTOTA0NGUXOGQ2ZTVIIIWIAW5ZZWN1CMUIOIIWIIWIBMV0IJOID3MILCJWYXROIJOIL05VDGLMX0NOYXQILCJWB3J0IJOINTUXODUILCJWCYI6IVCFH63WN4EWQEZYZWFRQ29UZMLNIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii4ljixmc43os4ymtiilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6iiisimlkijoiywezyzmwmtgtmjg4yi00nmyzlwfmmwmtota0nguxogq2ztviiiwiaw5zzwn1cmuioiiwiiwibmv0ijoid3milcjwyxroijoil05vdglmx0noyxqilcjwb3j0ijointuxoduilcjwcyi6ivcfh63wn4ewqezyzwfrq29uzmlniiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOII5MS4XMDCUMJE3LJIZNIISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIIXYMRJMWI4ZI0WYTIWLTRKYZGTOGY3MY1LMDA4ZJY0ZGE2NWUILCJUZXQIOIJ0Y3AILCJWYXROIJOIIIWICG9YDCI6IJIWODYILCJWCYI6IKBTZWXPX3BYB3H5EDIZ2LHZINIX2KFBJOKAJNIO24ZYTNIQ2LEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioii5ms4xmdcumje3ljizniisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioiixymrjmwi4zi0wytiwltrkyzgtogy3my1lmda4zjy0zge2nwuilcjuzxqioij0y3ailcjwyxroijoiiiwicg9ydci6ijiwodyilcjwcyi6ikbtzwxpx3byb3h5ediz2lhzinix2kfbjokajnio24zytniq2leilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9ss.txt |
| EYJHZGQIOIIXMDQUMJEUNJKUNDQILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC01MTE5NTI0MJQUBWNPDGVSLMNVIIWIAWQIOIJUYXNUZXQILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ3CYISINBHDGGIOIIVBMFZBMV0L2NKBIISINBVCNQIOII4MDGWIIWICHMIOIJNQ0KTQFYYCMF5QWXWAGETLTEYIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixmdqumjeunjkundqilcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc01mte5nti0mjqubwnpdgvslmnviiwiawqioijuyxnuzxqilcjpbnnly3vyzsi6ijailcjuzxqioij3cyisinbhdggioiivbmfzbmv0l2nkbiisinbvcnqioii4mdgwiiwichmioijnq0ktqfyycmf5qwxwagetlteyiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXNZIUNJCUMJA0LJG0IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJUYXNUZXQTNTEXOTUYNDI0LM1JAXRLBC5JBYISIMLKIJOIBMFZBMV0IIWIAW5ZZWN1CMUIOIIXIIWIBMV0IJOID3MILCJWYXROIJOIL25HC25LDC9JZG4ILCJWB3J0IJOIODA4MCISINBZIJOIQHYYCMF5BMD6ZW5KZWDPBWFTYWTWN5WK77IPIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixnziunjcumja0ljg0iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioijuyxnuzxqtntexotuyndi0lm1jaxrlbc5jbyisimlkijoibmfzbmv0iiwiaw5zzwn1cmuioiixiiwibmv0ijoid3milcjwyxroijoil25hc25ldc9jzg4ilcjwb3j0ijoioda4mcisinbzijoiqhyycmf5bmd6zw5kzwdpbwftywtwn5wk77ipiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOILZGDUM2YTYQTIX2LTAQDMGINIX2KFBJNQV2KFZHVCFKYH2CG5VD2XAIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioilzgdum2ytyqtix2ltaqdmginix2kfbjnqv2kfzhvcfkyh2cg5vd2xaiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMTE0LJK4LJAILCJHAWQIOIIWIIWIYWXWBII6IIISIMZWIJOIIIWIAG9ZDCI6IM5HC25LDC0XNJIXOTEWOTKUC2HHCMDOZGFPBHKUY28ILCJPZCI6IM5HC25LDCISIMLUC2VJDXJLIJOIMCISIM5LDCI6INDZIIWICGF0ACI6II9UYXNUZXQVY2RUP2VKXHUWMDNKMJU2MCISINBVCNQIOII4MDGWIIWICHMIOIJJUI1AVJJYYXLBBHBOYS0ZIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumte0ljk4ljailcjhawqioiiwiiwiywxwbii6iiisimzwijoiiiwiag9zdci6im5hc25ldc0xnjixotewotkuc2hhcmdozgfpbhkuy28ilcjpzci6im5hc25ldcisimluc2vjdxjlijoimcisim5ldci6indziiwicgf0aci6ii9uyxnuzxqvy2rup2vkxhuwmdnkmju2mcisinbvcnqioii4mdgwiiwichmioijjui1avjjyyxlbbhboys0ziiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIIXODGUMZQUMTK0LJE2NSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOIJGAWX0ZXITU2HJYW4ILCJUZXQIOIJZCGXPDGH0DHAILCJWYXROIJOILYISINBVCNQIOIIYMDGZIIWICHMIOIJABWVSAV9WCM94EXNYS9IX2YJYSDIN24ZIGIZYQNUM2LTYQTIXIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIIILCJ2IJOIMIJ9SS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiixodgumzqumtk0lje2nsisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioijgawx0zxitu2hjyw4ilcjuzxqioijzcgxpdgh0dhailcjwyxroijoilyisinbvcnqioiiymdgziiwichmioijabwvsav9wcm94exnys9ix2yjysdin24zigizyqnum2ltyqtixiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiiilcj2ijoimij9ss.txt |
| EYJHZGQIOIIYMC4XOTMUMTUZLJE5IIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIIILCJPZCI6IJM5YTHJMZC0LTC2YJETNGU5MC1HYJG1LTG1Y2Q5YTQYZGVKMIISIMLUC2VJDXJLIJOIMCISIM5LDCI6INRJCCISINBHDGGIOIIILCJWB3J0IJOIMTU4MZQILCJWCYI6IKLSLUBWMNJHEUFSCGHHLTEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IM5VBMUILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiiymc4xotmumtuzlje5iiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioiiilcjpzci6ijm5ythjmzc0ltc2yjetngu5mc1hyjg1ltg1y2q5ytqyzgvkmiisimluc2vjdxjlijoimcisim5ldci6inrjccisinbhdggioiiilcjwb3j0ijoimtu4mzqilcjwcyi6iklslubwmnjheufscghhlteilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6im5vbmuilcj2ijoimij9vless.txt |
| EYJHZGQIOIIYMTCUMJE3LJI1NS45OSISIMFPZCI6IJAILCJHBHBUIJOIIIWIZNAIOIIILCJOB3N0IJOIIIWIAWQIOII4MZA0OWJKYS04ZDUZLTQ0YMMTZJCXYY1MNMIWM2MXY2E0ODIILCJUZXQIOIJ3CYISINBHDGGIOIIVIIWICG9YDCI6IJG0NDMILCJWCYI6IKBHB2XLC3RHBL9WUE4GLSDWN6ABIIWIC2N5IJOIYXV0BYISINNUASI6IIISINRSCYI6IIISINR5CGUIOIITLS0ILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioiiymtcumje3lji1ns45osisimfpzci6ijailcjhbhbuijoiiiwiznaioiiilcjob3n0ijoiiiwiawqioii4mza0owjkys04zduzltq0ymmtzjcxyy1mnmiwm2mxy2e0odiilcjuzxqioij3cyisinbhdggioiiviiwicg9ydci6ijg0ndmilcjwcyi6ikbhb2xlc3rhbl9wue4glsdwn6abiiwic2n5ijoiyxv0byisinnuasi6iiisinrscyi6iiisinr5cguioiitls0ilcj2ijoimij9vless.txt |
| EYJHZGQIOIJMYXJ6YWQUDMLWZ3NTDGVHBS5PBMZVIIWIYWLKIJOIMCISIMFSCG4IOIIILCJMCCI6IIISIMHVC3QIOIJ6DWXHLMLYIIWIAWQIOII3ZJGYNTQ0NC00OWRKLTQXNGITY2RJMI1HYZY2NDNLOTEZNTAILCJPBNNLY3VYZSI6IJAILCJUZXQIOIJ0Y3AILCJWYXROIJOILYISINBVCNQIOIIZMZK1MYISINBZIJOISVITQFYYCMF5QWXWAGETMTEILCJZY3KIOIJHDXRVIIWIC25PIJOIIIWIDGXZIJOIIIWIDHLWZSI6IMH0DHAILCJ2IJOIMIJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjhzgqioijmyxj6ywqudmlwz3ntdgvhbs5pbmzviiwiywlkijoimcisimfscg4ioiiilcjmcci6iiisimhvc3qioij6dwxhlmlyiiwiawqioii3zjgyntq0nc00owrkltqxngity2rjmi1hyzy2ndnlotezntailcjpbnnly3vyzsi6ijailcjuzxqioij0y3ailcjwyxroijoilyisinbvcnqioiizmzk1myisinbzijoisvitqfyycmf5qwxwagetmteilcjzy3kioijhdxrviiwic25pijoiiiwidgxzijoiiiwidhlwzsi6imh0dhailcj2ijoimij9vless.txt |
| EYJZY3KIOIJHDXRVIIWIBMV0IJOIDGNWIIWIDHLWZSI6IMH0DHAILCJWYXROIJOIXC8ILCJWCYI6IIU0MEZSRUVFVLBOMDILMJALRJALOUYLOEQLQUMILCJOB3N0IJOIYM13LMNVBSISINBVCNQIOIIXNJYYMYISIMFKZCI6IJG1LJE3LJE5MI4XMTAILCJPZCI6IMVMOTG0ZDE5LTRKZJCTNDU5MI04Y2E4LWEZZJY1OGI3OGMWYSJ9VLESS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/eyjzy3kioijhdxrviiwibmv0ijoidgnwiiwidhlwzsi6imh0dhailcjwyxroijoixc8ilcjwcyi6iiu0mezsruvfvlbomdilmjalrjalouyloeqlqumilcjob3n0ijoiym13lmnvbsisinbvcnqioiixnjyymyisimfkzci6ijg1lje3lje5mi4xmtailcjpzci6imvmotg0zde5ltrkzjctndu5mi04y2e4lwezzjy1ogi3ogmwysj9vless.txt |
| HTTP | 451337 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/http.txt |
| HTTPS | 415844 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/https.txt |
| HY | 7 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy.txt |
| HY2 | 255 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/hy2.txt |
| SOCKS | 1 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks.txt |
| SOCKS4 | 437294 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks4.txt |
| SOCKS5 | 448542 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/socks5.txt |
| SS | 5527 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ss.txt |
| SSR | 80 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/ssr.txt |
| TROJAN | 6004 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/trojan.txt |
| TUIC | 2 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/tuic.txt |
| VLESS | 29611 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vless.txt |
| VMESS | 7296 | https://raw.githubusercontent.com/wiki/gfpcom/free-proxy-list/lists/vmess.txt |
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
