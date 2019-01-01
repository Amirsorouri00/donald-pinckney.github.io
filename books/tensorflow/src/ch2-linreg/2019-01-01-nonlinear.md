---
layout: bookpost
title: Nonlinear Regression
date: 2019-01-01
categories: TensorFlow
isEditable: true
editPath: books/tensorflow/src/ch2-linreg/2019-01-01-nonlinear.md
subscribeName: TensorFlow
---

<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  TeX: { equationNumbers: { autoNumber: "AMS" } }
});
</script>

# Nonlinear Regression

In chapters [2.3](/books/tensorflow/book/ch2-linreg/2018-03-21-multi-variable.html) and [2.4](/books/tensorflow/book/ch2-linreg/2018-11-15-feature-scaling.html) we saw how to adapt linear regression to work with multiple variables, and then used feature scaling to greatly improve the performance of the algorithm. However, we are still pretty limited in what sorts of regressions we can do, as we can only make linear predictions (with multiple variables). Let's see how we can extend our framework for linear regression to be able to do various nonlinear regressions, such as polynomials.


