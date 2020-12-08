Everybody and their grandma grew up studying the continuous Lyapunov equation

$$\mathbf{M}\mathbf{A} + \mathbf{A}^T\mathbf{M} = -\mathbf{Q}$$


where $$\mathbf{M}$$ and $$\mathbf{Q}$$ are symmetric positive definite matrices, and $$\mathbf{A}$$ is some square matrix. This equation comes up when you look at the stability properties of continuous linear dynamical systems. Namely, those systems which are described by 

$$\dot{\mathbf{x}} = \mathbf{A}\mathbf{x}$$

People also study the discrete Lyapunov equation

$$\mathbf{A}^T\mathbf{M}\mathbf{A} - \mathbf{M} = -\mathbf{Q}$$

Which comes from studying the discrete-time linear dynamical system:

$$\mathbf{x}_{t+1} = \mathbf{A}\mathbf{x}_{t}$$

To see where these Lyapunov equations comes from, check out this other post. 

In this post, we'll see how to go from the contiuous-time to discrete-time Lyapunov equation. I'll present a short derivation based on Taylor expansions. 

# Here is me typing something

Here is me typing something else. 



Here's an example of math:
$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$




