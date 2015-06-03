# 環境構築手順
### 事前準備
- 下記をインストール
1. [Dropbox](https://www.dropbox.com/ja/)
2. [keepassx](https://www.keepassx.org/downloads/)
3. xcode
4. [Karabinar](https://pqrs.org/osx/karabiner/index.html.ja)
5. `xcode-select --install`
6. `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
7. `brew doctor`
8. `brew update`
9. `brew install python ansible`
10. `mkdir .mac_provisioning`
11. `cd .mac_provisioning`
12. `HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -vv localhost.yml` でインストール
