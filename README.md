# 1行でLEMP環境構築
サーバに`root`ログインし１行のコマンドを実行するだけでDockerコンテナを使用したLEMPサーバ環境が構築できるスクリプトです。  

## 対象OS
- CentOS Linux v8
- Rocky Linux v8
- Alma Linux v8

## ライセンス

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

# 内容
Ansibleのローカル実行でDocker環境をインストールし、Dockerコンテナ上にLEMP環境を構築します。


## 主なインストールモジュール

### Docker環境

- docker-ce
- docker-ce-cli
- docker-compose

# 使い方
新規にOSをインストールしたサーバに`root`でログインし、以下の１行のコマンドをそのままコピーして実行します。

## 実行コマンド
```
curl https://raw.githubusercontent.com/czbone/oneliner-lemp-on-docker/master/script/build_env.sh | bash
```