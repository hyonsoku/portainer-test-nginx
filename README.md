# portainer-test-nginx

## 概要
このプロジェクトは、Portainerのテスト用に作成されたDockerコンテナスタックです。
nginxを含むDockerコンテナをデプロイし、Webサーバとして動作します。

本READMEでは、Dockerコンテナスタックをデプロイする手順を説明します。

## 動作環境

以下の環境で動作を確認しています。

- Docker 23.0.1
- Portainer 2.17.1

## 使用方法

1. Portainerにログインします。
2. ナビゲーションメニューから**Stack**をクリックし**Add stack**を選択します。
3. **Reposiotry URL**フィールドに、GitHubリポジトリのURLを入力します。
4. **Compose path**フィールドに、作成したDockerコンテナスタックの定義ファイルのパスを入力します。この例では`docker-compose.yml`を入力します。
5. **Deploy the stack**ボタンをクリックします。
6. スタックがデプロイされるまで待ちます。
7. ブラウザで`http://<PortainerホストのIPアドレス>`にアクセスし、nginxのウェルカムページが表示されることを確認します。

## ライセンス

MIT License (MIT)

Copyright (C) 2023 hyonsoku

本プロジェクトのライセンスについては、LICENSEファイルを参照してください。

## 作者
- GitHub: @hyonsoku
