**用chrome瀏覽器需要先安裝插件[MathJax Plugin for Github](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima/related)才能正常顯示數學公式**


# Lecture 1 #


# Lecture 2: Bias and Variance #

預測後的誤差有兩種來源：Bias或Variance。
當預測值(Estimator)的期望值等於實際值的時候稱為unbiased，例如平均值的估算。
而樣本變異數的期望值卻不會完全等於實際值的變異數，因此是biased的預測值。
> $m = \frac{1}{N}\sum_{}^{}x^n \neq \mu$，此時的m為unbiased的預測值
>
> 而樣本變異數則是$s^2 = \frac{1}{N}\sum_{}^{}(x^n-m)^2$，$s^2$可用來估測實際的變異數$\sigma^2$
>
> 但$s^2$的期望值並不完全等於$\sigma^2$，$s^2$的期望值等於$\frac{N - 1}{N}\sigma^2$
>
> 因此$s^2$是biased的預測值，通常比$\sigma^2$要小一點

