# Critical Point
## How to find Critical Points
Set $f_x$ and $f_y$ equal to $0$ and solve for $x$ and $y$.

## Classifying Critical Point 
Fact 1: If $Q(x,y)=Ax^2+Bxy+Cy^2$, then the graph of $Q$ is:
- a paraboloid if $4AC-B^2>0$. It's an upward paraboloid if $A>0$, and downwards if $A<0$.
- A saddle if $4AC-B^2<0$

Fact 2: The quadratic approximation of at a critical point $(a,b) is: 
$Q(x, y)=\frac{1}{2} f_{x x}(a, b)(x-a)^2+f_{x y}(a, b)(x-a)(y-b)+\frac{1}{2} f_{y y}(a, b)(y-b)^2+f(a, b)$
**Theorem**: Second derivative test for $f(x,y)$. Let $P=(a,b)$ be a critical point of $f(x,y)$. Assume that $f_{xx}$, $f_{yy}$, $f_{xy}$ are continous at $(a,b)$. ($D(a,b)$ represents discriminant in [[partial derivative]])
1. if $D(a,b)>0$, $f_{xx}(a,b)>0$, then $f(a,b)$ is a **relative min**.
2. if $D(a,b)>0$, $f_{xx}(a,b)<0$, then $f(a,b)$ is a **relative max**.
3. if $D(a,b)<0$, then $f$ has a saddle at $(a,b)$.
4. If $D(a,b)=0$, test is inconclusive (could be min, ma, or saddle).