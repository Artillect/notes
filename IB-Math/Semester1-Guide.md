##The Dot Product
$$\vec{a}\cdot\vec{b}=|\vec{a}||\vec{b}|\cos\theta=a_xb_x+a_yb_y
$$
If $\theta=90^\circ$ (The vectors are perpendicular), then $\vec{a}\cdot\vec{b}=0$

Rewritten, the dot product yields the equation:
$$
\cos \theta \frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}
$$
-This is used to find the angle between two vectors or to test if they are perpendicular

-The dot product is a scalar
##The Vector Equation of a Line
####Vector Equation:
$$
\vec{r}=\vec{b}+t\vec{b}
$$
####Parametric Equations:
$$
r_x=a_x+tb_x\\
r_y=a_y+tb_y
$$
####Cartesian Equation:
$$
y=mx+b
$$
-To find the cartesian equation, take the paramentric equations and solve for $t$. Set them equal to each other and solve for $y$.

-Consider an object moving in a straight line in the direction $\vec{v}<v_x,v_y>$
-If the object starts at position vector $\vec{a}=<a_x,a_y>$, then
$$
\vec{r}=\vec{a}+t\vec{v}
$$
-The speed of the object is the magnitude of $\vec{v}$

##The determinant of a matrix
-IDK how to explain this. Figure it out

##The Cross Product of Two Vectors
-So these are kinda weird. If $\vec{u}$ and $\vec{v}$ are put in a matrix as shown,
$$
\begin{bmatrix}
x & y & z \\
u_1 & u_2 & u_3 \\
v_1 & v_2 & v_3
\end{bmatrix}
$$
Then the determinant is:
$$
x
\begin{vmatrix}
u_2 & u_3 \\
v_2 & v_3
\end{vmatrix}
-y
\begin{vmatrix}
u_1 & u_3 \\
v_1 & v_3
\end{vmatrix}
+z
\begin{vmatrix}
u_1 & u_2 \\
v_1 & v_2
\end{vmatrix}
$$
-Some math later...
$$
\vec{u}\times\vec{v}=
\vec{i}
\begin{vmatrix}
u_2 & u_3 \\
v_2 & v_3
\end{vmatrix}
-\vec{j}
\begin{vmatrix}
u_1 & u_3 \\
v_1 & v_3
\end{vmatrix}
+\vec{k}
\begin{vmatrix}
u_1 & u_2 \\
v_1 & v_2
\end{vmatrix}
$$
-Written alternatively:
$$
\vec{u} \times \vec{v} = |\vec{u}||\vec{v}|\sin\theta \vec{n}
$$
-$\vec{n}$ is a unit vector that is perpendicular to $\vec{u}$ and $\vec{v}$
