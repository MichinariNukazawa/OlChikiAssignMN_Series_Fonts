OlChikiAssignMN Series Fonts
====
イラスト・デザイン向けオル・チキ文字フォント

## 概要
オル・チキ文字のフォントです。  
イラストおよびデザイン向けに、簡単に使えるオル・チキ文字フォントとして作成しました。  
商用可。  
本フォントは"[project daisy bell][pixiv_booth]"によるフォント製品です。  

ラテン・アルファベットの"A〜z"にオル・チキ文字を割り当ててあります。  
ふつうの英文にこのフォントを使用することで、オル・チキ文字で書かれた文章をデザインに使用することがとても簡単になります。  

フォントのデザインは[サンプル][ghpages_index]ページで見ることができます。  
姉妹フォントに[RuneAMN_Series_Font][ghpages_index_RuneAssignMN_Series_Fonts]があります。  


##より専門的な説明
A-zと一部の記号以外の、Latin1の領域は半角空白で埋めてあるため、記号はすべて空白になり表示されません。  
これは、ライセンスフリーな英文の長文を用意すれば、本フォントを適用するだけで、オル・チキ文字のみで書かれた文に見える絵が作れるということです。  
ライセンスフリーな英文に適用すればオル・チキ文字のみで書かれた文に見える絵を用意することができます。  
ただし、一部環境でデフォルトのフォントによる通常の記号に置き換わってしまう問題を確認しています。  
(Gimp2.8にて確認)  

本フォントは、A〜zを入力するだけで手軽にオル・チキ文字が使えるよう作成されました。  
オル・チキ文字に割り当てられているユニコード領域にはグリフを置いていません。  
また、すべてのオル・チキ文字を収録していません。(オル・チキ文字は45文字ありますが、今回フォントに収録したのは26文字+記号です。)  

参考：ラテン・アルファベット領域のアルファベットと記号  
!"#$%&'()*+,-./  
0123456789:;<=>?  
@ABCDEFGHIJKLMNO  
PQRSTUVWXYZ[¥]^_  
`abcdefghijklmno  
pqrstuvwxyz{|}‾  


## License
 本フォント製品のライセンス  
 
 イラスト・デザインに使用する場合、自由に使うことができます。ただし、責任は使用者が負うこととします。  
 ライセンスは予告なく変更される場合があります  

 本フォント製品のライセンスは、  
 姉妹フォントの[RuneAssignMN_Series_Font_free版のライセンス][readme_md_RuneAssignMN_Series_Fonts_license]に準ずるものとします。  
 (フォント名を読み替えてあとは等しい)  
 ライセンスの詳細は、そちらをお読みください。  

 ライセンスについて、よくわからない場合は、気軽に作者へ[メール(michinari.nukazawa@gmail.com)][mailto]にて、お問い合わせください。  

##スクリプト「svg_splitter.pl」について。
本プロジェクトに含まれるスクリプト「svg_splitter.pl」は、
『mashabow＠しろもじ作業室（http://shiromoji.net, mashabow@shiromoji.net）』  
様の公開してくださっているスクリプトを元に作成したものです。  
(今回の用途に供するために、明らかに間違っている方法を含んだいくつかの変更を当てました。)


##フォント制作手順
全自動ではなく、手作業が含まれています。  
作業環境はIllustraterを除いてLinux(Ubuntu14.04)を想定しています。  
 * Illustraterでフォントデザイン
 * Illustrater上でアウトライン化・標準SVG(1.2)で出力
 * フォント生成スクリプト(fonts_generate.pl)でフォントを生成

グリフの形状が壊れる場合、手順中でアウトライン化の際に、以下の方法で解決する場合があります。  
 * アウトライン化のあとでパスファインダーによる結合を行う(グループ化を解除してください)。
 * グリフが1000x1000の領域から飛び出していないか確認してください。
どうしても直らない場合、作者に連絡をいただければ、対応できるかもしれません。  


##謝辞
以下のサイトを参考にさせていただきました。  

しろもじ作業室 の日本語かなフォント作成記事とスクリプト  
http://d.hatena.ne.jp/mashabow/20120314/1331744357

FontForge 公式ドキュメント  
http://fontforge.org/ja/

オル・チキ文字のUnicode表  
http://www.unicode.org/charts/PDF/U1C50.pdf

Wikipedia のオル・チキ文字の記事  
http://en.wikipedia.org/wiki/Ol_Chiki_alphabet

Deciphering the runes 研究ページ  
http://wiki.puella-magi.net/Deciphering_the_runes

IllustraterABC TIPSページの補填記事のIllustraterの設定  
http://www.slowgun.org/abc/ts12.html


##LICENSE About
Please read Japanese licence text.  
Font use illustration and design to Select to "2-clause BSD license" or "daisy_ANM free font license"(original).  
Font introduces can use this project included image files. and please notation "Licence", "Creater"
 and mean to "Have possibilities update, add new font and other. prease read original page.", and link this page.  
Font file redistribution to please read Japanese licence text.  

##連絡先
[michinari.nukazawa@gmail.com][mailto]

Develop by Michinari.Nukazawa, in Project "daisy bell".
[ghpages_index]: http://michinarinukazawa.github.io/OlChikiAssignMN_Series_Fonts/
[ghpages_index_RuneAssignMN_Series_Fonts]: http://michinarinukazawa.github.io/RuneAssignMN_Series_Fonts/
[readme_md_RuneAssignMN_Series_Fonts_license]: https://github.com/MichinariNukazawa/RuneAssignMN_Series_Fonts/#user-content-license
[blog_article]: http://blog.michinari-nukazawa.com/
[mailto]: mailto:michinari.nukazawa@gmail.com
[pixiv_booth]: https://daisy-bell.booth.pm/
