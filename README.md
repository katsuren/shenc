shenc
=====

shows character encode

[概要]
ファイルの文字コードを出力する。
show encode の略。

[使い方]
ファイルまたはディレクトリを指定する。
ディレクトリを指定した場合は再帰的にファイルを検索する。
（例）
  $ shenc hoge.txt
    [Shift-JIS] : hoge.txt
  $ shenc dir
    [BINARY] : dir/hoge.gif
    [ASCII] : dir/hoge.rtf
    [UTF-8] : dir/foo/fuga.txt

[システム要件]
nkf がインストールされていること。
  - Linux なら yum install nkf
  - MacOSX なら brew install nkf とか port install nkf とか
===============================================================
※nkf は、The nkf Projectによる、文字コードの変換を行うプログラムです。
詳細は以下のサイトをご覧下さい。
　http://sourceforge.jp/projects/nkf/
===============================================================

[免責]
このスクリプトの使用は自己責任とする。
このスクリプトを使って発生したいかなる損害についても責任を負わない。

[ライセンス]
MIT License
