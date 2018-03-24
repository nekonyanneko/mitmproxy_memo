# mitmproxy_memo
## mitmproxy
 - Maind in the Middle proxy
    - http,https,ssh,tcpの通信の中身を見れるproxy

## 環境構築
 1. sudo passwd root
 2. sudo update
 3. sudo apt-get update
 4. sudo apt-get -y upgrade
 5. sudo apt-get -y install build-essential
 6. sudo apt-get -y install python3-pip
 7. sudo pip3 install -U pip
 8. sudo pip3 install mitmproxy
 9. mitmproxy github cloneする
 10. tar展開
 11. ブラウザのプロキシ設定でホストとポートを指定
 12. ブラウザでアクセスし、caを取得
 13. wgetでproxyを通したい場合、.wgetrcにプロキシとcaのパスを設定する

## 今後
 - 独自プロキシサーバとしてログを取り続けられるマシンがほしい
 - プロキシサーバの構築
 - 目的の情報を蓄積
 - 解析

## メモ
 - 特定のドメインに対してリダイレクトも可能なため、urlfilteringのような事もできる

