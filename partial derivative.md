# Partial Derivative
The partial [[derivative]] of $f(x,y)$ wtih respect to $x$ is
$$\frac{\partial f}{\partial x}=f_x(x, y)=\lim _{h \rightarrow 0} \frac{f(x+h, y)-f(x, y)}{h}$$
provided this limit exists.
Similarly, the partial derivative of $f(x,y) with respect to $y$ is
$$\frac{\partial f}{\partial y}=f_y(x, y)=\lim _{h \rightarrow 0} \frac{f(x, y+h)-f(x, y)}{h}$$
provided this limit exists.
- $f_x(a,b)$ is the instantaneous rate of change at $f$ at the point $(a,b)$ in the x-direction.
- $f_x(a,b)$ is the slope of the tangent line to $f(x,b)$ at the point $x=a$

## Higher-Order Partial Derivatives
Taking partial derivative of partial derivative
$$(f_x)_x=f_{xx} \rightarrow \frac{\partial}{\partial x}(\frac{\partial f}{\partial x})=\frac{\partial^2 f}{\partial x^2}$$, concavity of the trace when y = something
$$f_{yy}=\frac{\partial^2 f}{\partial y^2}$$, concavity of the trace with x = something
$$(f_x)_y=f_{xy} \rightarrow \frac{\partial^2 f}{\partial y \partial x}$$
$$f_{yx}=\frac{\partial^2 f}{\partial x \partial y}$$
## Derivatives of functions of several values (NOT SURE WHAT REAL NAME IS)
$$\frac{\partial f}{\partial s}=\frac{\partial f}{\partial x} \cdot \frac{\partial x}{\partial s} + \frac{\partial f}{\partial y} \cdot \frac{\partial y}{\partial s} + \frac{\partial f}{\partial z} \cdot \frac{\partial z}{\partial s}$$
## Clairaut's Theorem
If the second particals of $f$ are continuous, then you can differentiate in any order.
$$f_{xy}=f_{yx}$$
## Fermat’s Theorem
If $f(x,y)$ has a local extremum at $(a,b)$, then $f_x(a,b)=0$ or $f_y(a,b)=0$.

If $f(x,y)$ has a critical point at $(a,b)$, then $\nabla f(a,b)=\langle 0,0 \rangle$.
- local min if $f''(x,y) > 0$
- local max if $f''(x,y) < 0$
- inconclusive if $f''(x,y)=0$
![[prototypical behaviors critical point.png]]
### Discriminant
Used to determine if a critical point is a maximum (positive), minimum (negative), or saddle point (zero).

The discriminant of $f$ at $(a, b)$ is
$$
D=D(a, b)=f_{x x}(a, b) f_{y y}(a, b)-\left[f_{x y}(a, b)\right]^2 .
$$