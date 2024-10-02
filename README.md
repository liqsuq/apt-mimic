# apt-mimic
オフライン環境でUbuntuをアップデートしたりインストールする必要があり作成した、ローカルリポジトリSSDを作るためのスクリプトセットです。[apt-mirror](https://github.com/apt-mirror/apt-mirror)を使用しています。

適当なストレージデバイスに配置してmirror.listを編集、`./update`を実行してインターネットからパッケージを取得します。その後に任意のコンピュータにストレージを接続して`./attach`/`./detach`すれば取得したパッケージ群を利用可能になります。
