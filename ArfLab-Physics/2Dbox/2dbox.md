#TwoDBox

The **TwoDBox** function visualizes Schrodinger's ψ 2D particle box. It uses the **ArfLab** and **matplotlib** libraries to perform this operation.

- Wave equation analysis and visualization

$$
\psi(x,y) = \frac{2}{\sqrt{L_x L_y}} \sin\left(\frac{n_x \pi x}{L_x}\right) \sin\left(\frac{n_y \pi y}{L_y}\right)
$$

-  Energy levels of a particle in a two-dimensional cubic box

$$
E = \frac{\pi^2 \hbar^2}{2m} (n_x^2 + n_y^2 + n_z^2)
$$

```bash

TwoDBox(Lx=2.0, Ly=1.5, nx=4, ny=1, N=100)

```
  

---