# LTC_modeling
The code and dataset accompanying the paper *"Exploring the Lattice Thermal Conductivity Model via Interpretable Machine Learning"* will be completed and made available after the paper is accepted.

$
log(\kappa)_{KAN} = 4.78 \cdot \Big( 
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
$
