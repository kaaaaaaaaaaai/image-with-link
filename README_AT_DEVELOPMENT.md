### npmへのpublish方法

npm adduser
git tag -a v1.0.0 -m "My first version v1.0.0"
git push origin tags/v1.0.0
npm publish ./


### 開発開始手順
yarn install

node server.jsでアップロードAPIを起動
だけど、uploadしたURLが絶対パスになってしまうので修正が必要
決め打ちで画像を戻している。
