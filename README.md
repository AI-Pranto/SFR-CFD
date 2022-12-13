# SFR-CFD
Thermal hydraulic analysis of SFR fuel assembly

### Material property
- $\rho = 1016.82 -0.239 \times T$
- $C_{p} = 1629.1 - 0.83267 \times T + 0.00046208 \times T^2$
- $k = 105.1843 -0.049 \times T$
- $\mu = 0.00385 - 1.66448e-5 \times T + 3.00411e-8 \times T^2 - 2.48661e-11 \times T^3 + 7.8085e-15 \times T^4$

### In ANSYS CFX
- $\rho = (1016.82 - 0.239 \times T \times 1 [K^-1]) \times 1 [kg m^-3]$
- $C_{p} = (1629.1 - 0.83267 \times (T \times 1 [K^-1]) + 0.00046208 \times (T \times 1 [K^-1])^2) \times 1 [J kg^-1 K^-1]$
- $k = (105.1843 - 0.049 \times (T \times 1 [K^-1])) \times 1[W m^-1 K^-1]$
- $\mu = (0.00385 - 1.66448e-5 \times (T \times 1 [K^-1]) + 3.00411e-8 \times (T \times 1 [K^-1])^2 - 2.48661e-11 \times (T \times 1 [K^-1])^3 + 7.8085e-15  \times(T \times 1 [K^-1])^4) \times 1[Pa \cdot s]$
