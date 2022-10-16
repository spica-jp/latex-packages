# LaTeX_Reportレポジトリ
LaTeXで作成したレポートや自作パッケージ類を置く（予定）

## 自作パッケージ
### exenumitem-jp.sty
+ enumitemパッケージをベースにしたリスト系環境の拡張パッケージ
+ enumerate環境における箇条の番号の書式の拡張がメイン
+ ①，②，③，…／あ，い，う，…／ア，イ，ウ，…／い，ろ，は，…／イ，ロ，ハ，…などが利用可能
+ LuaLaTeXでの使用が推奨
+ pLaTeX・upLaTeXでも利用できるように暫定的には対処済み
+ パッケージのオプションとして`loadonly`，`platex`，`uplatex`を用意：`usepackage[loadonly]{exenumitem-jp}`などとすればよい
+ `loadonly`未指定時は，番号の付き方などを`exenumitem-jp`側で設定
+ `loadonly`指定時は，番号の付き方などの設定は変更しない設定
+ Beamerでは利用不可（enumitemが非対応のため）
