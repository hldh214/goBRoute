# goBRoute

## Description

B-RouteのAPIを使って、電力情報を取得するツールです。

## Requirement

* goのインストールをしておいてください
* B-Routeのアカウントを取得してください

## Install

```
git clone https://github.com/hldh214/goBRoute.git
cd goBRoute
go get
GOOS=linux GOARCH=arm GOARM=5 go build main.go
```

## Credit

* [higebu/wattmonitor](https://github.com/higebu/wattmonitor)
* [BP35A1](http://www.rohm.co.jp/web/japan/products/-/product/BP35A1)
* [Armadillo-Box WS1(旧 IIJ SA-M0)で遊ぶ準備をする](https://www2.hatenadiary.jp/entry/2023/04/26/202125)
* [armadillo-box-ws1_product_manual](https://manual.atmark-techno.com/armadillo-box-ws1/armadillo-box-ws1_product_manual_ja-1.1.7/)
