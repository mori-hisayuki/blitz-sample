# React Container

## 環境変数

`.devecontainer`の直下に`devcontainer.env`ファイルを配置すると読み込まれる。

`devcontainer.env`がないとコンテナ起動時にエラーになるため、空でも用意する。

## Githubへの接続

Githubへ接続する際のSSHキー`***`と`***.pub`を追加する キーは`ssh-keygen`コマンドで作成 作成したkeyでの接続情報をknown_hostsに追加する

```
ssh-keyscan github.com >> ~/.ssh/known_hosts
```

接続情報が追加されたknown_hostsをsshディレクトリに追加する

## awsへの接続

AWSへ接続する際の`config`と`credentials`を追加する
