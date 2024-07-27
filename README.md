\begin{cases}
1 & -1 \leq t \leq 1 \\
0 & \text{otherwise}
\end{cases} \]
**through an FM scheme, where \(\Omega_c = 10000\pi\), \(k_f = 100\pi\), and \(A = 1\).**
#### a) Write the explicit expression for the FM signal \(s_{FM}(t)\).
To write the explicit expression for the FM signal, we need to use the formula for FM modulation:
\[ s_{FM}(t) = A \cos\left( \Omega_c t + k_f \int_{-\infty}^{t} x(\tau) \, d\tau \right) \]
Given \( x(t) = 1 \) for \(-1 \leq t \leq 1\) and 0 otherwise, we calculate the integral of \(x(t)\) over the specified interval.
\[
\int_{-\infty}^{t} x(\tau) \, d\tau =
\begin{cases}
0 & t < -1 \\
t + 1 & -1 \leq t \leq 1 \\
2 & t > 1
\end{cases}
