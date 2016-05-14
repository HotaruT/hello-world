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

## 参考文献
+ [GitHub Guides のチュートリアル (Hello World)](https://guides.github.com/activities/hello-world/)
+ [Markdown記法 チートシート](http://qiita.com/Qiita/items/c686397e4a0f4f11683d)


