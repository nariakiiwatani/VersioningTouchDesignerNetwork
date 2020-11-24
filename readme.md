# VersioningTouchDesignerNetwork

TouchDesignerのネットワーク構造とノードの設定をhuman-readableなファイル群に展開し、差分をgit等のバージョン管理ツール上で確認できるようにするためのツールです。

`.toe`や`.tox`の全情報をアーカイブすることは目的とせず、「バージョン管理したい情報」をピックアップして保存することを目指しています。

![example screenshot](https://user-images.githubusercontent.com/1306139/99188335-cba77f00-279e-11eb-92a7-3d5970af2016.png)

# How to use

`NetworkExpander.toe`を自分のネットワークにドラッグアンドドロップするだけです。  
パラメータにいくつか設定項目があるので、必要に応じて設定してください。  
![NetworkExpander Parameters](https://user-images.githubusercontent.com/1306139/99188190-fb09bc00-279d-11eb-9d98-fc77462cc341.png)

# etc...

全情報の保存と復元をする場合はオフィシャルツールの[toeexpand](https://docs.derivative.ca/Toeexpand)と[toecollapse](https://docs.derivative.ca/Toecollapse)を使うことをお勧めします。  
このうちtoeexpandについては、git-hookのpre-commitタイミングで使えるようにしたものが[こちら](https://github.com/nariakiiwatani/toeexpand-git-pre-commit)にあります。  
