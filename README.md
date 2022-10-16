# LaTeX_Reportレポジトリ
LaTeXで作成したレポートや自作パッケージ類を置く（予定）

## 自作パッケージ
### exenumitem-jp.sty
+ enumerate環境における箇条の番号の書式の拡張がメイン
+ ①，②，③，…／あ，い，う，…／ア，イ，ウ，…／い，ろ，は，…／イ，ロ，ハ，…などが利用可能
+ 現状LuaLaTeX専用
+ pLaTeX・upLaTeXでも一応通るように暫定的に対処する予定
+ パッケージのオプションとして`loadonly`を用意：`usepackage[loadonly]{exenumitem-jp}`とすればよい
+ `loadonly`未指定時は，番号の付き方などを設定
