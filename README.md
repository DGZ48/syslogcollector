# syslogcollector
家のルーターがなんかおかしい（接続端末のWifiが切れたり）。ログを分析しようにも接続端末が多くノイズが多くて、落ち着いて見れない。
syslog出力できるので、これをかき集めてkibanaで見てみたい。
## 想定構成
Router -> fluentd -> elasticsearch -> kibana
## メモ
### fluentd
#### Input syslog
[fluentdのsyslogプラグインを使ってsyslogプロトコルでログを受け取る](https://qiita.com/suzuki-navi/items/2410ebdf92279996c516)
### elasticsearch
### kibana
