# <center>数学分析</center>
<font size=5 face=楷体>$$
y''\left( x+y'^2 \right) =y'\text{在}y\left( 1 \right) =y'\left( 1 \right) =1\text{时的特解}
$$ 
---
## 1.第一步
&ensp;&ensp;&ensp;&ensp;另y'=u,则原方程变为
$$
u'\left( x+u^2 \right) =u
$$
## 2.第二步
&ensp;&ensp;&ensp;&ensp;想分离变量,但发现x与u无法完全分离。而此方程并非线性微分方程，无法使用线性微分方程解的结构。但事实真的如此吗？事实上可以将$u'$除到右边，方程变为：
$$
x+u^2=u\times x'
$$这样就成为以$u$为自变量的线性微分方程。
## 3.第三步
&ensp;&ensp;&ensp;&ensp;利用公式得
$$
\left( \frac{x}{u} \right) '=1
$$&ensp;&ensp;&ensp;&ensp;进而有
$$
x=y'^2+cy'
$$&ensp;&ensp;&ensp;&ensp;代入初始条件
&ensp;&ensp;&ensp;&ensp;有：
$$
x=y'^2
$$&ensp;&ensp;&ensp;&ensp;最终得到
$$
y=\frac{2}{3}x^{\frac{3}{2}}+1
$$
