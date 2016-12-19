#Vectors
##The Dot Product
$$\vec{a}\cdot\vec{b}=|\vec{a}||\vec{b}|\cos\theta=a_xb_x+a_yb_y
$$
If $\theta=90^\circ$ (The vectors are perpendicular), then $\vec{a}\cdot\vec{b}=0$

Rewritten, the dot product yields the equation:
$$
\cos \theta= \frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}
$$
-This is used to find the angle between two vectors or to test if they are perpendicular

-The dot product is a scalar
##Equations of Lines (2D)
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
-$\vec{n}$ is a unit vector that is perpendicular to $\vec{u}$ and $\vec{v}$, which means that the cross product of two vectors yields a vector. To find the magnitude of the cross product vector, use the following equation:
$$
|\vec{u}\times \vec{v}|=|\vec{u}||\vec{v}|\sin{\theta}
$$

-The area of a triangle formed by vectors $\vec{a}$ and $\vec{b}$ can be solved as follows:

$$
\text{area}=\frac{1}{2}|\vec{a}||\vec{b}|\sin \theta
$$

##Equations of Lines (3D)
####Vector Equation:
$$
\vec{r}=\vec{a}+t\vec{b}
$$
-Note that this is different from the vector equation of a 2D line because the vectors here are 3D
-Rewriting the Vector Equation in each individual dimension gives the parametric equations
####Parametric Equations:
$$
x=x_0+at \\
y=y_0+bt\\
z=z_0+ct\\
$$
-Solving for $t$ and setting each equation equal to each other gives:
####Cartesian Form
$$
t=\frac{x-x_0}{a}=\frac{y-y_0}{b}=\frac{z-z_0}{c}
$$
##Planes in Space (3D)
A plane can be determined from:
- three non-colinear points
- two instersecting lines
- a line and a point not on the line
####Normal Form
$$
\vec{n} \cdot \vec{r} =\vec{n}\cdot \vec{r_0}
$$
Where $\vec{n}$ is orthoganal to the plane and $\vec{r}$ and $\vec{r_0}$ are position vectors of a point in the plane

####Scalar Equation
$$
a(x-x_0)+b(y-y_0)+c(z-z_0)=0
$$
-rewriting the standard form of a plane yields the cartesian form, which is shown in one of two ways: the general or standard form
####Cartesian Forms
#####General Form:
$$
ax+by+cz+d=0
$$
#####Standard Form:
$$
ax+by+cz=d
$$
-Both the standard form and general form are both types of the cartesian form
####Vector Parametric
-Vector parametric is a linear combination of two vectors $\vec{p}$ and $\vec{q}$ in the plane. $\vec{a}$ is the position vector of a point in the plane
$$
\vec{r}=\vec{a}+\lambda\vec{p}+\mu \vec{q}
$$

-Note that $\vec{p}\times\vec{q}$ give a vector in a direction perpendicular to the plane

##Distances between points, lines, and planes
####Distance between a point $P$ and a line
$$
D=\frac{|\vec{AP}\times \vec{v}|}{|\vec{v}|}
$$
where $\vec{v}$ is the direction vector of the line and $\vec{AP}$ a vector from a point on the line to point $P$
####Distance between a point $P$ and a plane
$$
D=\frac{\vec{AP}\cdot \vec{n}}{|\vec{n}|}
$$
where $\vec{n}$ is normal to the plane and $\vec{AP}$ is a vector from a point on the plane to point $P$

If the plane is written in general cartesian form, then the following equationcan be used:
$$
D=\frac{|ax_1+by_1+cz_1+d|}{\sqrt{a^2+b^2+c^2}}
$$
where point $P$ is a position vector $<x_1,y_1,z_1>$

-I forgot how to do lines and cant read my notes. You should probably know that for the test though
