# 使い方

```bash
git clone https://github.com/f-ttok/beamer-ja.git
cd beamer-ja
xelatex main.tex
```

## フォントの設定
linuxの人はMeiryoとSegoe UIがインストールされていないので `\setsansfont` `\setCJKsansfont` の中を適当に変えましょう

```latex
\setsansfont[Scale=0.92]{Noto Sans}
\setCJKsansfont[Scale=0.92]{Noto Sans JP}
```

## 色のカスタマイズ
テーマのオプションに色を16進数でわたすと色を変えられる．

```latex
\usetheme[
  primary=317589,
  accent=DC5E4A,
  example=343537,
  fg_default=222222,
  bg_default=fffffc,
]{simple}
```

※ 上記の色の設定は [メインカラーとアクセントカラーを、簡単にセンス良くまとめる方法（the power of powerpoint）](http://thepopp.com/easy-and-good-way-to-choose-colors-for-powerpoint/) を参考にした
