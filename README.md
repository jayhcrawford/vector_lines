# Mastering Parametric Vectors and Lines

This is your complete study guide for parametric vectors and lines in multivariable calculus. It includes all essential forms, equations, and explanations you need to master the topic.

---

## 1. Parametric Equation of a Line
A line in 3D space can be described parametrically as:

$$
\vec{r}(t) = \vec{r}_0 + t\vec{v}
$$
- $\vec{r}_0$: Position vector of a point on the line
- $\vec{v}$: Direction vector
- $t$: Parameter (real number)

Or in coordinates:

$$
\begin{cases}
  x = x_0 + a t \\
  y = y_0 + b t \\
  z = z_0 + c t
\end{cases}
$$

Where $(x_0, y_0, z_0)$ is a point on the line and $(a, b, c)$ are the components of the direction vector.

---

## 2. Symmetric (Cartesian) Form of a Line
If $a, b, c \neq 0$:

$$
\frac{x - x_0}{a} = \frac{y - y_0}{b} = \frac{z - z_0}{c}
$$
- Useful for eliminating the parameter $t$.

---

## 3. Vector Form of a Line

$$
\vec{r} = \vec{r}_0 + t\vec{v}
$$

- Same as parametric, but emphasizes vector notation.

---

## 4. Line Through Two Points
Given points $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$:
- Direction vector: $\vec{v} = (x_2 - x_1, y_2 - y_1, z_2 - z_1)$
- Parametric equation:

$$
\vec{r}(t) = \vec{A} + t(\vec{B} - \vec{A})
$$

Or in coordinates:

$$
\begin{cases}
  x = x_1 + (x_2 - x_1)t \\
  y = y_1 + (y_2 - y_1)t \\
  z = z_1 + (z_2 - z_1)t
\end{cases}
$$

---

## 5. Intersection of Two Lines
To find if two lines intersect, set their parametric equations equal and solve for parameters.
- If a solution exists, the lines intersect at that point.
- If not, they are skew or parallel.

---

## 6. Distance Between Two Skew Lines
Given lines $L_1$ and $L_2$:

$$
\text{Distance} = \frac{|(\vec{r}_2 - \vec{r}_1) \cdot (\vec{v}_1 \times \vec{v}_2)|}{|\vec{v}_1 \times \vec{v}_2|}
$$

Where $\vec{r}_1, \vec{r}_2$ are points on $L_1, L_2$ and $\vec{v}_1, \vec{v}_2$ are their direction vectors.
---

## 7. Angle Between Two Lines
Given direction vectors $\vec{v}_1, \vec{v}_2$:

$$
\cos \theta = \frac{\vec{v}_1 \cdot \vec{v}_2}{|\vec{v}_1||\vec{v}_2|}
$$

---

## 8. Projection of a Point onto a Line
Given point $P$ and line $\vec{r}(t) = \vec{r}_0 + t\vec{v}$:
- Find $t$ such that $\vec{r}(t)$ is closest to $P$:

$$
t = \frac{(\vec{P} - \vec{r}_0) \cdot \vec{v}}{|\vec{v}|^2}
$$

- The projection is $\vec{r}_0 + t\vec{v}$.

---

**Tip:** Always identify a point and a direction vector to use these equations effectively.

---

## Summary Cheat-Sheet
| Concept | Equation |
|---|---|
| Parametric Line | $\vec{r}(t) = \vec{r}_0 + t\vec{v}$ |
| Symmetric Line | $\frac{x - x_0}{a} = \frac{y - y_0}{b} = \frac{z - z_0}{c}$ |
| Line Through Two Points | $\vec{r}(t) = \vec{A} + t(\vec{B} - \vec{A})$ |
| Intersection of Lines | Set parametric equations equal, solve for $t$ |
| Distance Between Skew Lines | $\frac{\rvert(\vec{r}_2 - \vec{r}_1) \cdot (\vec{v}_1 \times \vec{v}_2)\lvert}{\rvert\vec{v}_1 \times \vec{v}_2\lvert}$ |
| Angle Between Lines | $\cos \theta = \frac{\vec{v}_1 \cdot \vec{v}_2}{\lvert\vec{v}_1\rvert\lvert\vec{v}_2\rvert}$ |
| Projection onto Line | $\vec{r}_0 + \left(\frac{(\vec{P} - \vec{r}_0) \cdot \vec{v}}{\lvert\vec{v}\rvert^2}\right)\vec{v}$ |

This covers all the equations and forms you need to master parametric vectors and lines.
