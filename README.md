# LTC_modeling
The code and dataset accompanying the paper *"Exploring the Lattice Thermal Conductivity Model via Interpretable Machine Learning"* will be completed and made available after the paper is accepted.

$
\log(\kappa)_{KAN} = 4.78 \cdot \Big( 
    0.01 \cdot \arctan(7.93 \cdot \gamma - 3.22) 
    - 0.02 \cdot \text{atanh}(1.65 \cdot F - 1.02) 
    - 1 
    + 0.05 \cdot \exp(-100.0 \cdot (-\Theta - 0.04)^2) 
    - 0.03 \cdot \exp(-92.16 \cdot (-C_v - 0.06)^2) 
    - 0.02 \cdot \exp(-40.96 \cdot (-C_p - 0.06)^2) 
    + 0.02 \cdot \exp(-2.9 \cdot (0.22 - K_i)^2) 
    - 0.02 \cdot \exp(-38.44 \cdot (0.07 - S_v)^2) 
    - 0.04 \cdot \exp(-60.69 \cdot \alpha^2) 
\Big)^4 
- 0.16 \cdot \tanh\Big( 
    -0.26 \cdot \sin(5.58 \cdot SG + 6.4) 
    + 0.53 \cdot \tan(1.34 \cdot F - 9.54) 
    + 0.69 \cdot \tanh(7.9 \cdot C_p - 2.41) 
    + 0.5 \cdot \tanh(10.0 \cdot C_v - 3.2) 
    + 0.32 \cdot |9.94 \cdot S_v - 0.82| 
    + 0.86 \cdot \arctan(4.61 \cdot K_s - 1.72) 
    + 0.29 
    - 81.47 \cdot \exp(-100.0 \cdot (-\alpha - 0.16)^2) 
    + 2.09 \cdot \exp(-100.0 \cdot (-\Theta - 0.08)^2) 
    + 0.17 \cdot \exp(-100.0 \cdot (0.54 - \gamma)^2) 
    - 1.45 \cdot \exp(-14.44 \cdot (0.12 - K_i)^2) 
\Big) 
- 0.08 \cdot \tanh\Big( 
    2.45 \cdot \tan(1.08 \cdot F - 0.8) 
    + 1.27 \cdot \tan(1.77 \cdot K_i - 0.76) 
    + 0.95 \cdot \tan(1.87 \cdot K_s - 0.84) 
    + 0.78 \cdot \tan(1.77 \cdot S_v + 2.4) 
    + 0.03 \cdot \tan(3.17 \cdot \Theta + 1.57) 
    + 0.37 \cdot \tanh(4.25 \cdot SG - 2.9) 
    - 1.15 
    - 0.66 \cdot \exp(-43.72 \cdot (0.27 - \gamma)^2) 
    - 0.32 \cdot \exp(-100.0 \cdot (0.24 - \alpha)^2) 
    + 0.67 \cdot \exp(-100.0 \cdot (0.02 - C_p)^2) 
    + 0.72 \cdot \exp(-100.0 \cdot C_v^2) 
\Big) 
- 0.07 \cdot \Big| 
    0.22 \cdot \sin(10.0 \cdot \gamma + 1.0) 
    - 0.75 \cdot \tan(2.34 \cdot K_s - 0.97) 
    + 0.34 \cdot \tanh(10.0 \cdot F - 4.9) 
    - 0.34 \cdot \arctan(10.0 \cdot \Theta - 0.6) 
    + 0.37 \cdot \text{atanh}(2.6 \cdot C_p - 0.95) 
    + 1.52 
    - 0.27 \cdot \exp(-8.1 \cdot (0.41 - SG)^2) 
    + 0.42 \cdot \exp(-49.0 \cdot (0.2 - S_v)^2) 
    - 0.92 \cdot \exp(-100.0 \cdot (0.14 - \alpha)^2) 
    + 0.42 \cdot \exp(-100.0 \cdot (0.13 - K_i)^2) 
    - 0.93 \cdot \exp(-81.0 \cdot (0.07 - C_v)^2) 
\Big| 
- 4.57 
- 0.21 \cdot \exp\Big( 
    -1.86 \cdot \Big(
        -0.03 \cdot \tan(3.11 \cdot K_s - 7.81) 
        - 0.02 \cdot \tan(3.4 \cdot SG + 4.4) 
        - 0.14 \cdot \tan(4.26 \cdot \alpha + 7.97) 
        - 0.12 \cdot |7.59 \cdot \Theta - 1.03| 
        - 0.18 \cdot \arctan(7.53 \cdot \gamma - 4.87) 
        + 0.16 \cdot \text{atanh}(2.0 \cdot F - 1.08) 
        - 0.08 
        + \exp(-2.56 \cdot (-K_i - 0.03)^2) 
        + 0.28 \cdot \exp(-88.36 \cdot (0.09 - S_v)^2) 
        - 0.16 \cdot \exp(-100.0 \cdot (0.04 - C_v)^2) 
        - 0.23 \cdot \exp(-100.0 \cdot (0.04 - C_p)^2) 
    \Big)^2
\Big) 
- \dots
$
