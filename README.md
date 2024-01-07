# gui applications
ホストがWindowsで、GUIアプリケーションをdockerコンテナ内で動かすときに使う環境。

## 手順
- ホスト側
  - [vcxsrv](https://sourceforge.net/projects/vcxsrv/)をインストール
  - XLaunchを起動
  - 基本的にはそのままで、Disable access controlにチェックを入れるのを忘れない。

- コンテナ側
  - devcontainer.jsonが基本的にやってくれるはずなのでxeyesを起動して動作確認だけする