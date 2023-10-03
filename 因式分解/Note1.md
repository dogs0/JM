## 公式/模型
又一个大坑  
**忽略了定义**  
## 命题
(1) $\forall a,b \in R, (a+b)^2=a^2+2ab+b^2$  
(1.1) $\forall a,b,c \in R, (a+b+c)^2=a^2+b^2+c^2+2ab+2bc+2ac$   
(1.2) $\forall a_1,a_2,a_3,...,a_n \in R, (\Sigma_{i=1}^n a_i)^2=\Sigma_{i=1}^n a_i^2 + \Sigma_{j=1}^n 2 a_j a_{\[(j+1 \quad mod \quad n)+1]}$  

(2) $\forall a,b \in R, (a+b)^3=a^3+3a^2b+3ab^2+b^3$  
(2.1) $\forall a,b,c \in R, (a+b+c)^3=a^3+b^3+c^3+3a^b+3ab^2+3b^2c+3bc^2+3a^2c+3ac^2+2abc$  

(3) $\forall a,b \in R, a^2-b^2=(a+b)(a-b)$
> 推导:  
> $a^2-b^2$  
> $=a^2+ab-b^2-ab$  
> $=a(a+b)-b(a+b)$  
> $=(a+b)(a-b)$  

(4) $\forall a,b \in R, a^3-b^3=(a-b)$  
> 推导:  
> $a^3-b^3$  
> $=a^3+a^2b+ab^2-b^3-b^2a-ba^2$  
> $=a(a^2+ab+b^2)-b(a^2+ab+b^2)$
> $=(a-b)(a^2+ab+b^2)$

(4.1) $\forall a,b \in R, c \in N_{+}, a^n-b^n=(a-b)(\Sigma_{i=0}^{n-1} a^{i}b^{n-1-i})$  

(5) $\forall a,b,c,d,e,f,g \in R, a=de, c=fg, b=df+eg \Rightarrow ax^2+bx+c=dex^2+dfx+egx+fg=(dx+g)(ex+f)$  
(就是十字相乘)

(6) 令 $f(x)=\Sigma_{i=0}^n a_i x^i (\forall a_i \in R)$, 且 $\exists c \in R, f(c)=0$ 都有(x-c)是f(x)的因式  
> 证:
> 设f(x)除以(x-c)商为Q(x),余r.
> 则f(x)=(x-c)Q(x)+r   
> $f(c)=(c-c)Q(x)+r=r$   
> 所以若f(c)=0  
> 则 $f(x) \equiv 0 (mod \quad x-c)$  

(6.1) 令 $c=\frac{p}{q}$ (pq互质) ,则 $p| a_0$ , $q| a_n$  
