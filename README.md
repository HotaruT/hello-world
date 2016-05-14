# hello-world
はじめてのGitHub

## このリポジトリについて
[GitHub Guides のチュートリアル](https://guides.github.com/activities/hello-world/)をみながら、GitHubの使い方を試してみるのです。  
ついでに、Markdown記法についてもお勉強。
## 数式
Qiitaで使えるという数式は、使えるのだろうか。
```Math
\frac{5}{10} = \frac{1}{2}
```
インライン数式 $x^2 + y^2 = 1$ はどうだろう。

……どちらもダメっぽい。

### MathJax導入
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}
});
</script>
<script type="text/javascript" async src="path-to-mathjax/MathJax.js?config=TeX-AMS_CHTML"></script>
<script src='https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML'></script>
\\[ \\sum_{k=1}^{n}k = \\frac{n+1}{2} \\]

## GitHub Pages
[GitHub Pages](https://pages.github.com/)のやり方をみながらページを公開してみる。
（もともとは[Githubを使って3分でHPを公開する。](http://qiita.com/budougumi0617/items/221bb946d1c90d6769e9)を参照して
公式ページに辿り着いた。）

### 作ったページ
+ [最初のページ](http://hotarut.github.io/hello-world/)
+ [オイラーフォントのおためし](http://hotarut.github.io/hello-world/eulerfont.html)

## 参考文献
+ [GitHub Guides のチュートリアル (Hello World)](https://guides.github.com/activities/hello-world/)
+ [Markdown記法 チートシート](http://qiita.com/Qiita/items/c686397e4a0f4f11683d)
+ [Githubを使って3分でHPを公開する。](http://qiita.com/budougumi0617/items/221bb946d1c90d6769e9)

