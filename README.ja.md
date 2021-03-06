Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Sample Code for SP601

SP601通信確認用のSiTCPサンプルソースコードです。

SiTCPの利用するAT93C46のインタフェースをSP601のEEPROM(M24C08)に変換するモジュールを使用しています。

パラメータSYSCLK_FREQ_IN_MHzは、クロックの周波数をMHz単位の整数で入力してください。 


## SiTCP とは

物理学実験での大容量データ転送を目的としてFPGA（Field Programmable Gate Array）上に実装されたシンプルなTCP/IPです。

* SiTCPについては、[SiTCPライブラリページ](https://www.bbtech.co.jp/products/sitcp-library/)を参照してください。
* その他の関連プロジェクトは、[こちら](https://github.com/BeeBeansTechnologies)を参照してください。

![SiTCP](sitcp.png)
