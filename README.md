# WordListGenerator
英語論文から単語を抽出&amp;登場回数順にソートし、さらに意味も載った単語帳まで作ってみた。

詳しい説明(Qiita)
https://qiita.com/mkunu/items/9b59e77de964a109e46b


## プログラムの構成
0. 論文pdfを収集。
1. 各pdfをそれぞれtxtに変換。
2. 作った各txtを１つにまとめる。
3. txt内の各単語の登場回数を調べる。
4. Mac内蔵辞書を使って単語帳（登場回数順）の作成。


## 参考サイト 
1. 各pdfをそれぞれtxtに変換。  
 - 大量のPDFファイルを、pdfminerを使ってtextファイルに変換する  
https://qiita.com/monchy-monchy/items/85ded85423be6108f05b  
 - PDFMinerでPDFから日本語テキストを抽出する  
https://qiita.com/korkewriya/items/72de38fc506ab37b4f2d
2. 作った各txtを１つにまとめる。  
 - 同上
3. txt内の各単語の登場回数を調べる。  
 - 英単語帳作成～その2～  
http://kuroyagi.hatenablog.com/entry/2017/10/07/202830
4. Mac内蔵辞書を使って単語帳（登場回数順）の作成。  
 - Python Tips： Mac の辞書アプリを Python から利用したい  
https://www.lifewithpython.com/2016/07/python-use-mac-dictionary-app.html
