---
title: "Api"
date: 2021-07-24T13:47:12+08:00
draft: flase
summary: "This is the api summary"

---
### Journal reports
#### https://api.scrapyer.com/maria/s
- Method: **GET**
- params:
```
{
    "db" : "journals",
    "t" : "reports",
    "q" : string,
}
```
- Response
```
 Headers: Content-Type:application/json
 Body:
{
  "items": [{"name":string,"jif":string,"issn":string}...],
  "total_count": int
}
```
#### https://api.scrapyer.com/esp32/rtc
- Method: **GET**

- Response
```
 Headers： Content-Type:application/json
 Body:
{
 {"year":int,"mon":int,"day":int,"wday":int,"hour":int,"min":int,"sec":int}
}
```
---
###  File system
#### https://file.scrapyer.com

- Method: **GET**

### Ports
#### printer
- [printer-cups] ```6_631```
- [printer-v2raya] ```17```
#### mac
- [mac_v2raya_socks5] ```1_2017```
- [mac_mariadb] ```3306```
- [mac_redis] ```6379```
- [mac_docsify] ```3000```
#### arch
- [arch_v2raya] ```80_17```
- [arch_jupyter] ```88```
