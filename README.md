# Vagrant on Docker の開発環境

Docker Desktop for Mac (Docker for Mac)の動作が遅いので Vagrant に乗り換えたら幸せになれました。

## 環境

- macOS (Mojave, Catalina で確認、Windows 10 も行けるはず)
- VirtualBox
- Vagrant
  - Ubuntu 18.04 LTS
  - Docker
  - Docker Compose

※階層え仮想環境の中身を表現しています

## 実行方法

予め Vagrant の環境を作成しておいてください。

```bash
git clone https://github.com/MasanoriIwakura/vagrant-docker.git
cd vagrant-docker

# VM立ち上げ
vagrant up

# VMにssh
vagrant ssh

# VM終了
vagrant halt
```
