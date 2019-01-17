# 練習メニュー
## 第１弾
以下の基本構成のアプリを作成。
* postgresql  1台
* web-api  1台
* nginx  1台

web-apiとnginxをスケール可能とし、replicasを2で運用し、Ingressで公開する。

## 第２弾
第１弾の構成を本番／SI1／SI2の3環境分作る。
リリースのしやすさとか管理のしやすさを見てみよう。
