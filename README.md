# LTC_modeling
The code and dataset accompanying the paper *"Exploring the Lattice Thermal Conductivity Model via Interpretable Machine Learning"* will be completed and made available after the paper is accepted.

$$
\begin{align*}
\log(\kappa)_{\text{KAN}} = & \, 4.78 \left( 0.01 \arctan(7.93\gamma - 3.22) - 0.02 \text{arctanh}(1.65F - 1.02) - 1 \right. \\
& + 0.05 \exp(-100.0(-\Theta - 0.04)^2) - 0.03 \exp(-92.16(-C_v - 0.06)^2) \\
& - 0.02 \exp(-40.96(-C_p - 0.06)^2) + 0.02 \exp(-2.9(0.22 - K_i)^2) \\
& - 0.02 \exp(-38.44(0.07 - S_v)^2) - 0.04 \exp(-60.69\alpha^2) \Big)^4 \\
& - 0.16 \tanh\Big( -0.26\sin(5.58SG + 6.4) + 0.53\tan(1.34F - 9.54) \\
& + 0.69\tanh(7.9C_p - 2.41) + 0.5\tanh(10.0C_v - 3.2) \\
& + 0.32 |9.94S_v - 0.82| + 0.86\arctan(4.61K_s - 1.72) + 0.29 \\
& - 81.47\exp(-100.0(-\alpha - 0.16)^2) + 2.09\exp(-100.0(-\Theta - 0.08)^2) \\
& + 0.17\exp(-100.0(0.54 - \gamma)^2) - 1.45\exp(-14.44(0.12 - K_i)^2) \Big) \\
& - 0.08 \tanh\Big( 2.45\tan(1.08F - 0.8) + 1.27\tan(1.77K_i - 0.76) \\
& + 0.95\tan(1.87K_s - 0.84) + 0.78\tan(1.77S_v + 2.4) \\
& + 0.03\tan(3.17\Theta + 1.57) + 0.37\tanh(4.25SG - 2.9) - 1.15 \\
& - 0.66\exp(-43.72(0.27 - \gamma)^2) - 0.32\exp(-100.0(0.24 - \alpha)^2) \\
& + 0.67\exp(-100.0(0.02 - C_p)^2) + 0.72\exp(-100.0C_v^2) \Big) \\
& - 0.07 \left| 0.22\sin(10.0\gamma + 1.0) - 0.75\tan(2.34K_s - 0.97) + 0.34\tanh(10.0F - 4.9) \right. \\
& - 0.34\arctan(10.0\Theta - 0.6) + 0.37\text{arctanh}(2.6C_p - 0.95) + 1.52 \\
& - 0.27\exp(-8.1(0.41 - SG)^2) + 0.42\exp(-49.0(0.2 - S_v)^2) \\
& - 0.92\exp(-100.0(0.14 - \alpha)^2) + 0.42\exp(-100.0(0.13 - K_i)^2) \\
& - 0.93\exp(-81.0(0.07 - C_v)^2) \Big| - 4.57 \\
& - 0.21 \exp\Big( -1.86 \big( -0.03\tan(3.11K_s - 7.81) - 0.02\tan(3.4SG + 4.4) \\
& - 0.14\tan(4.26\alpha + 7.97) - 0.12|7.59\Theta - 1.03| - 0.18\arctan(7.53\gamma - 4.87) \\
& + 0.16\text{arctanh}(2.0F - 1.08) - 0.08 + \exp(-2.56(-K_i - 0.03)^2) \\
& + 0.28\exp(-88.36(0.09 - S_v)^2) - 0.16\exp(-100.0(0.04 - C_v)^2) \\
& - 0.23\exp(-100.0(0.04 - C_p)^2) \big)^2 \Big) \\
& - 0.53 \exp\Big( -12.72 \big( 0.04\sin(5.04SG + 2.18) + 0.11\tan(2.64K_s + 4.81) \\
& - 0.08\tan(2.77\Theta - 4.58) + 0.32\tanh(9.0\alpha - 0.44) - 0.1\tanh(10.0\gamma - 6.6) \\
& - 0.34\arctan(2.52F - 1.63) + 0.15\arctan(9.0S_v - 1.56) + 0.04\text{sign}(2.64 - 10.0C_p) \\
& - 1 - 0.43\exp(-21.25(-K_i - 0.1)^2) + 0.11\exp(-81.0(0.15 - C_v)^2) \big)^2 \Big) \\
& + 0.04 \exp\Big( -10.71 \big( 0.17\sin(6.2C_p - 0.15) + 0.12\arctan(5.2S_v - 3.27) \\
& + 0.04\text{sign}(4.06 - 9.4\gamma) + 0.03\text{sign}(9.0 - 10.0SG) - 1 \\
& + 0.97\exp(-96.04(-\alpha - 0.07)^2) - 0.65\exp(-100.0(-C_v - 0.06)^2) \\
& - 0.41\exp(-11.5(0.95 - \Theta)^2) - 0.21\exp(-5.76(0.38 - F)^2) \\
& + 0.44\exp(-3.24(0.14 - K_s)^2) + 0.62\exp(-1.96(0.05 - K_i)^2) \big)^2 \Big)
\end{align*}

$$

