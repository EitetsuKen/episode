﻿# episodeのまとめ方

- ひとつのフォルダに次の5点を入れる

1. main.tex
2. maegaki.tex
3. atogaki.tex
4. kyouritu.cls
5. 全員分の原稿TeXファイル

- main.texに全員の原稿を入れる

\subfile{ファイル名}  
のようにして全員の原稿を読み込ませる

- 前書き･あとがき等を編集する

- main.texをコンパイルする

platex main  
platex main  
dvipdfmx main  
等でできる．2回コンパイルしないと目次が更新されない（定理等の番号付けが2回コンパイルしないと反映されないのと同じ理屈）．ただし，いちいちこれを打つのも大変なので，Makefileを使うと良いかもしれない．詳しくは
https://texwiki.texjp.org/?Make

- その他

表紙は別ファイルpdfで良いと思われる．

- 印刷

学生会館で印刷する．手順は以下の通り．

0. 原本を用意する．
1. ゲスプリンターで一気に刷る．
2. 刷りあがった紙を重ねる．
3. 重ねたものを中綴じ折り機で製本する．

注意A．2で紙を重ねるときにコレーターを使うと
（コレーターがポンコツなせいで）かえって時間がかかる場合がある．
2018年度五月祭においては人力で重ねる作業を実施した．

注意B．製本工程において人手が要る時間と要らない時間がある．
例えば，0や1の作業は1人でもできるが，2の作業には10人は欲しい．
また，紙を運んだりできあがったものを持ち帰ったりするのにも人手が要る．

注意C．できあがった本を入れておく箱があると良い．

注意D．所要時間は4時間をみておくと良い．
2018年度五月祭では14:00-18:00に実施した．

学生会館の機器については以下を参照のこと．

ゲスプリンター

https://www.gkuc.net/?page=%A5%B2%A5%B9%A5%D7%A5%EA%A5%F3%A5%BF%A1%BC%A4%F2%BB%C8%A4%A6

印刷関連機器（中綴じ折り機含む）

https://www.gkuc.net/?page=%B0%F5%BA%FE%B4%D8%CF%A2%B5%A1%B4%EF%A4%F2%BB%C8%A4%A6