<!--MathJax的配置脚本，用于临时简单的配置 -->
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    extensions: ["tex2jax.js"],
    <!--输入Latex公式，以HTML和CSS的形式显示输出 -->
    jax: ["input/TeX", "output/HTML-CSS"],
    tex2jax: {
      <!--$表示行内元素，$$表示块状元素 -->
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
      processEscapes: true
    },
    "HTML-CSS": { availableFonts: ["TeX"] }
  });
</script>
<!--加载MathJax的最新文件， async表示异步加载进来 -->
<script type="text/javascript" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js">
</script>

# Exercise 2.2
$$
  A=\begin{bmatrix}
  0 & 1\\
  1 & 0
\end{bmatrix}
$$

$$
  A=\begin{bmatrix}
  0 & 1\\\
  1 & 0
\end{bmatrix}
$$
