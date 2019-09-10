<script type="text/x-mathjax-config">MathJax.Hub.Config({tex2jax:{inlineMath:[['\$','\$'],['\\(','\\)']],processEscapes:true},CommonHTML: {matchFontHeight:false}});</script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML"></script>
# マルコフ連鎖モンテカルロ法と詳細釣り合い条件

## 詳細釣り合い条件とは何か
マルコフ連鎖モンテカルロ法を用いるとき, ある分布 $P(x)$ をマルコフ連鎖の定常分布とする遷移確率 $\pi(x)$ を設計する必要がある. つまり以下の関係を満たす$\pi(x)$を設計する必要がある.
$$
P(x^{\prime}) = \Sigma_{x}P(x)\pi(x \to x^{\prime})
$$
例えば$()^{T}$