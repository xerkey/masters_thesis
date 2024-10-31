# KS-degree

## ファイル構成
### 本文関連
- ./main.tex : title.tex, abstract.tex, chapterX.texを集約するファイルです。ビルドの際に指定してください。
- ./title.tex : 表紙を記述します。
- ./abstract.tex : アブストラクトを記述します。
- ./chapter : 各"chapterX.tex"に章を分けて記述します。
- ./image : 論文内で使用する図を格納します。
- ./Master-paper.bib : 引用文献を記述します。

### フォーマット
jecon.bstがフォーマットファイルです。

### ビルド時の設定ファイル
latexmkrcがビルド時の設定ファイルです。
環境の設定によって使用されるかされないのかが変わるので注意。
例えば~/.latexmkrcがすでに存在していればプロジェクト内のlatexmkrcがなくても問題はない可能性がある。
またVS codeを使用していてsettings.jsonでlatexmkrcを使用しない設定もあり得る。