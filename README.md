# latex-packages
LaTeXの自作パッケージ類

## `skmetro.sty`
metropolisをベースにしたBeamer用パッケージです。

### 対応状況
#### LaTeXエンジン
日本で主に使用されるpLaTeX、upLaTeX、LuaLaTeXに対応しています。

使用エンジンは自動判定されますが、pLaTeX使用時は`platex`を、upLaTeX使用時には`uplatex`を、LuaLaTeX使用時には`lualatex`をオプションに指定しても構いません。

### さらに知るには
その他詳細はPackage Documentationを参照してください。

## `skenumitem.sty`
`enumitem`パッケージの拡張パッケージです。

特に`enumerate`環境における箇条番号書式の拡張がメインとなっており、具体的には、

+ ①、②、③、…
+ あ、い、う、…
+ ア、イ、ウ、…
+ い、ろ、は、…
+ イ、ロ、ハ、…
+ 全角ローマ数字（Ⅰ、Ⅱ、Ⅲ、…／ⅰ、ⅱ、ⅲ、…）
+ 全角アラビア数字（１、２、３、…）

が利用可能となります。

### 対応状況
#### LaTeXエンジン
日本で主に使用されるpLaTeX、upLaTeX、LuaLaTeXに対応しています。

使用エンジンは自動判定されますが、pLaTeX使用時は`platex`を、upLaTeX使用時には`uplatex`を、LuaLaTeX使用時には`lualatex`をオプションに指定しても構いません。

#### ドキュメントクラス
jclasses、jsclasses、ltjsclasses、jlreqに対応しています。

### `loadonly`オプション
パッケージのオプションとして`loadonly`を用意しています。

`loadonly`未指定時は、番号の付き方などを`skenumitem`側で再設定しますが、`loadonly`指定時は、番号の付き方などの設定変更を行いません。

---

## リリースノート
### `skmetro.sty`
#### 2023/02/10
エンジンの自動判定を行うようにしました。

### `skenumitem.sty`
#### 2023/02/10
エンジンの自動判定を行うようにしました。
