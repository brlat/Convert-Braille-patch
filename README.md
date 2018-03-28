# Bug fix and modifications to Convert-Braille-0.05 > Convert::Braille perl module

This is my attempt to bug-fix and add some changes to Convert::Braille perl module by Daniel Yacob. I really thank you for your wonderful work. I'm blind and I use braille all day and every day for my daily life. 

- [Convert::Braille - search.cpan.org](http://search.cpan.org/~dyacob/Convert-Braille-0.05/lib/Convert/Braille.pm)

I changed following:

- %BrailleAsciiToUnicode =( ... ','	=> '⠄', in Braille.pm, to ','	=> '⠠',
- '\''	=> '⠠', in the same part, to '\''	=> '⠄',

## Convert::Brailleモジュールのバグ修正と機能追加

perlのcpanでインストールできるConvert::BrailleモジュールでASCII点字をUnicode点字に変換するとき、3の点と6の点が逆になっていたのでこれを作りました。

Windowsのポータブル版があるStrawberry perlの場合次のようにしてConvert::Brailleがインストールできます。

> cpan Convert::Braille

インストール後に下記の場所にあるBraille.pmを置き換えます。

> ./perl/site/lib/Convert/Braille.pm

## Copyright

perlと同じ。


