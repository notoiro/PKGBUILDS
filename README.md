# PKGBUILDS
自分用に書き換えたり作ったりしたPKGBUILD詰め合わせ

## LIST
`*`がついてるものは私が書いたやつ。

### kwrite-old
KDEのテキストエディタ

公式の[Kateパッケージ](https://archlinux.org/packages/extra/x86_64/kate/ )に置き換えられる以前のバージョンのKwriteのKwrite部分だけを切り出してパッケージ名修正してビルド通るようにしたやつ。

https://apps.kde.org/kwrite/

### alcom*
高速なオープンソースの[VRChat Creator Companion](https://vcc.docs.vrchat.com )の代替ツール

tar.gzからビルドすると.gitがなくてエラー出るのでコミットハッシュ取得してる部分にパッチを当ててます。
~~公式にAppImageしかなかったのでビルドスクリプトいじってdebでビルドする形でパッケージ化。適当に書いたDesktop Entry付き。~~

https://github.com/vrc-get/vrc-get/blob/master/vrc-get-gui/README.md

### plasma6-wallpaper-switcher*
Plasma6で仮想デスクトップごとに壁紙設定できるようにするやつ

バージョン番号不明。Gitのブランチからビルドしてるし作ってテスト終わった後に`-git`なパッケージだなぁって思った。

https://github.com/martenjj/wallpaperswitch

## License
改変したものは元のライセンス通り、私が書いた物はCC0
