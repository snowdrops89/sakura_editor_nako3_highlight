# なでしこ３用サクラエディタのシンタックスハイライト及び各種定義ファイル
　これは、[サクラエディタ](https://sakura-editor.github.io/)用、[日本語プログラミング言語　なでしこv3](https://nadesi.com/top/)の、シンタックスハイライト、キーワードヘルプ、入力補完機能を設定するためのファイル群です。

　サクラエディタ用のファイルですが、ほぼ単なる単語のリストと正規表現なので、他のエディタのなでしこ用のハイライトを作る際にも、役に立つかも知れません。

　命令群は、なでしこv3用ですが、助詞、記号、予約語といったハイライトの基本的な部分は、v1もほとんど変わりありませんから流用出来ます。

# 内容
　まあ、ファイル名が日本語なんで、見た通りなんです。

- なでしこv3強調キーワード_助詞.kwd
- なでしこv3強調キーワード_記号.kwd
- なでしこv3強調キーワード_予約語.kwd
- なでしこv3強調キーワード_命令.kwd（入力補完にも使います）
- なでしこv3正規表現キーワード.rkw
- なでしこv3キーワードヘルプ.khp
- なでしこv3アウトライン解析.rul
- なでしこv3色設定_黒背景.col
- なでしこv3.ini

# 導入

- 「設定 ＞ タイプ別設定一覧 ＞ インポート」
  - 「なでしこv3.ini」を選んで開く。
  - 「新規追加」「そのままインポート」「OK」

※色設定はもちろん好みの物に変えてもよきです。

※個別に設定する場合は、[サクラエディタのヘルプ](https://sakura-editor.github.io/help/HLP000001.html)を参照するか、[Qiita](https://qiita.com/snowdrops89/items/c9f5941ed1ad30a6272e)に、なんかかんか書いてます。

## 注意
　正規表現キーワードを使用するので、「bregexp(bregonig.dll)」が必要になります。

　タイプ別設定 ＞ 正規表現キーワード で、右肩にナニか「bregonig.dll」のバージョンが記載されていれば、入っています。

　無いよ的なことが書かれていたならば、[ここ](http://k-takata.o.oo7.jp/mysoft/bregonig.html)から「bron420.zip」をダウンロードしてきて、サクラエディタのEXEと同じトコに置きます。

# らいせんす
　的なものは特にないので、ご利用はすべて自己責任で、ご自由にどうぞ。

　もちろん、「サクラエディタ」「なでしこ」は、それぞれの規約に従って利用して下さいね。

　なでしこが、もっと流行るといいなぁ～☆
