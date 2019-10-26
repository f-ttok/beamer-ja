# 使い方

```bash
git clone https://github.com/f-ttok/beamer-ja.git
cd beamer-ja
xelatex main.tex
```

## フォントの設定
`\setsansfont` `\setCJKsansfont` をいじると，フォントを変えられる．
デフォルトはUbuntuの標準フォントにしてあるので，Windowsの人は，コメントをつけたり外したりして調節してください．

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
