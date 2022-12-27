# latex-packages
LaTeXの自作パッケージ類

## skmetro.sty
+ metropolisをベースにしたBeamer用パッケージ
+ 日本語への対応も含む
+ LuaLaTeXでの使用を強く推奨
+ pLaTeX・upLaTeXでも使用可能
+ pLaTeX使用時は`platex`を，upLaTeX使用時には`uplatex`をオプションに指定すること：`\usepackage[uplatex]{skmetro}`などとすればよい
+ 詳細はPackage Documentationを参照のこと

## skxenumitem.sty
+ `enumitem`パッケージをベースにしたリスト系環境の拡張パッケージ
+ `enumerate`環境における箇条の番号の書式の拡張がメイン
+ ①，②，③，…／あ，い，う，…／ア，イ，ウ，…／い，ろ，は，…／イ，ロ，ハ，…などが利用可能
+ LuaLaTeXでの使用が推奨
+ pLaTeX・upLaTeXでも利用できるように暫定的には対処済み
+ jclasses，jsclasses，ltjsclasses，jlreqでの動作は確認済み
+ パッケージのオプションとして`loadonly`，`platex`，`uplatex`を用意：`\usepackage[loadonly]{exenumitem-jp}`などとすればよい
+ `loadonly`未指定時は，番号の付き方などを`exenumitem-jp`側で設定
+ `loadonly`指定時は，番号の付き方などの設定は変更しない
+ pLaTeX使用時は`platex`を，upLaTeX使用時には`uplatex`をオプションに指定すること：`\usepackage[uplatex]{exenumitem-jp}`などとすればよい
