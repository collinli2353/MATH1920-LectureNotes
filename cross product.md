# Cross Product
Binary operation on two [[vector]] in a 3D space.
Only works in $\mathbb{R}^2$

### Properties of the Cross Product

- $\vec{v} \times \vec{w}$
- {${\vec{v},\vec{w},\vec{v}\times\vec{w}}$} form a right-hand system
- $\left|\left|\vec{v}\times\vec{w}\right|\right|$ is the area of the parallelogram spanned by $\vec{v}$ and $\vec{w}$

### Calculating Cross Product Manually

Simple Determinat Calcultaion: $$
\left|\begin{array}{ll}
a & b \\
c & d
\end{array}\right|=a d-b c
$$
$$
\mathbf{v} \times \mathbf{w}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
v_1 & v_2 & v_3 \\
w_1 & w_2 & w_3
\end{array}\right|=\left|\begin{array}{cc}
v_2 & v_3 \\
w_2 & w_3
\end{array}\right| \mathbf{i}-\left|\begin{array}{cc}
v_1 & v_3 \\
w_1 & w_3
\end{array}\right| \mathbf{j}+\left|\begin{array}{cc}
v_1 & v_2 \\
w_1 & w_2
\end{array}\right| \mathbf{k}
$$

### Theorem 1: Geometric Description of the Cross Product

Given two nonzero nonparallel vectors $v$ and $w$ witih angle $\theta$ between them, the cross product $v\times w$ is the unique vector with the following three properties:

- $v\times w$ is orthogonal to $v$ wand $w$
- $v\times w$ has length $\left|\left|v\right|\right| \left|\left|w\right|\right|\sin{\theta}$

### Theorem 2: Basic Properties of the Cross Product

- $w\times v=-v\times w$
- $v\times v=0$
- $v\times w=0$ if and only if either $w=\lambda v$ for some scalar $\lambda$ or $v=0$
- $(\lambda v)\times w=v\times(\lambda w)=\lambda(v\times w)$
- $(u+v)\times w=u\times w+v\times w \\ u\times (v+w)=u\times v+u\times w$

### Theorem 3: Volume via Scalar Triple Product and Determinants

Let $\mathbf{u}, \mathbf{v}, \mathbf{w}$ be nonzero vectors in $\mathbf{R}^3$. Then the parallelepiped $\mathscr{D}$ spanned by $\mathbf{u}, \mathbf{v}$, and $\mathbf{w}$ has volume
$$
V=|\mathbf{u} \cdot(\mathbf{v} \times \mathbf{w})|=\left|\operatorname{det}\left(\begin{array}{c}
\mathbf{u} \\
\mathbf{v} \\
\mathbf{w}
\end{array}\right)\right|
$$
![parallelepiped image](https://i.imgur.com/TWomeXk.png)