<font size="4">$$ \left\{
\begin{aligned}
&Regression&&MSE&&均方誤差\\
&Classification&&gini&&Entropy熵(亂度)
\end{aligned}
\right.
$$

<font size="4">$$
\begin{aligned}
MSE=\sum(每一點-平均)^2
\\
距離平均越進，預測越準\\
MSE\downarrow，整齊程度\uparrow\\
\end{aligned}
$$

<font size="4"><font color="#dd0000">$$
\begin{aligned}
回歸有一個問題:&無法衡量多個模型\\
\end{aligned}
$$

<font size="4"><font color="#dd0000">$$
\begin{aligned}
\rightarrow \frac ab&=\frac {\sum(pre-真實)^2}{\sum(平均-真實)^2}&(normalize)\\
a&:誤差值\\
b&:總和\\
\end{aligned}
$$

<font size="4"><font color="#006600">$$特別點\left\{
\begin{aligned}
&\frac ab=0\rightarrow a=0\rightarrow pre=真實(好)\\
&\frac ab=1\rightarrow a=b\rightarrow pre=平均(爛)\\
\end{aligned}
\right.
$$

<font size="4"><font color="#006600">$$
\begin{aligned}
r^2&score=1-\frac ab=\left\{ 
\begin{aligned}
1&(好)\\
0&(爛)
\end{aligned}
\right.
\end{aligned}
$$
