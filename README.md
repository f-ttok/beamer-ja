# 使い方

```bash
git clone https://github.com/f-ttok/beamer-ja.git
cd beamer-ja
xelatex main.tex
```

# その他のメモ
- linuxの人はMeiryoとSegoe UIがインストールされていないので `\setsansfont` `\setCJKsansfont` の中を適当に変えましょう
```latex
\setsansfont[Scale=0.92]{Noto Sans}
\setCJKsansfont[Scale=0.92]{Noto Sans JP}
```
