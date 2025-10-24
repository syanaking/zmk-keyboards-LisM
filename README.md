

[公式ドキュメント](https://zmk.dev/docs/development/local-toolchain/setup/container?container=vsCode)

zmk (ZMKソースリポジトリクローンしたディレクトリ)
zmk-modules (Docker)

### DevContainer内でMakefileを使用してローカルでビルド

#### yqインストール
macOS
```
brew install jq
```

Ubuntu/Debian
```
apt update && apt install -y jq
```

#### ビルド実行

```
make -f /workspaces/zmk-modules/zmk-keyboards-LisM/Makefile
```

クリーン
```
make clean -f /workspaces/zmk-modules/zmk-keyboards-LisM/Makefile
```