## GmailApi
gmail apiを使うためのpythonモジュールを作成

## 使い方
```
$ cd ~/workspace
$ git clone https://github.com/hiranoo/GmailApi.git
```
helpers.py内部で各種モジュールをインポートしているため```from helpers import *```ですべてインポート

## gmail api Oauth2.0 client secret key
google cloud platformにて作成、ダウンロード
https://console.cloud.google.com/apis/credentials
有効期限は最終更新時刻から1日
失効すると、画面操作で再取得する必要があるので自動化に支障あり

ローカル端末の以下に配置すること
```~/workspace/GmailApi/credentials.json```








