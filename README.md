# 简介

Forked from [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)，本项目每天0点自动生成 MaxMind mmdb 格式文件`GeoLite2.mmdb`

[![Build GeoLite2.mmdb](https://github.com/Krew1nd/geoip/actions/workflows/build.yml/badge.svg)](https://github.com/krew1nd/geoip/actions/workflows/build.yml)

## 与官方版 GeoIP 的区别

- 中国大陆 IPv4 地址数据使用 [IPIP.net](https://github.com/17mon/china_ip_list/blob/master/china_ip_list.txt)、[纯真CN数据库](https://raw.githubusercontent.com/metowolf/iplist/master/data/special/china.txt)
- 包含特殊类别：
  - `GEOIP,TWITTER`
  - `GEOIP,NETFLIX`
  - `GEOIP,TELEGRAM`
  - `GEOIP,GOOGLE`
  - `GEOIP,PRIVATE`

## 下载地址

- **GeoLite2.mmdb**：
[https://raw.githubusercontent.com/Krew1nd/geoip/release/GeoLite2.mmdb](https://raw.githubusercontent.com/Krew1nd/geoip/release/GeoLite2.mmdb)
- **GeoLite2.mmdb.sha256sum**：
[https://raw.githubusercontent.com/Krew1nd/geoip/release/GeoLite2.mmdb.sha256sum](https://raw.githubusercontent.com/Krew1nd/geoip/release/GeoLite2.mmdb.sha256sum)

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
