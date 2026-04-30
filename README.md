(1) These codes were translated into Python as a personal side project and serve as a demonstration of a more advanced version originally developed in MATLAB. The inputs and dimensions used in this code are intentionally not based on real data.
--
(2) The 1D model developed by Zavaliangos et al. (2017), “Prediction of Air Entrapment in Tableting: An Approximate Solution,” has been reproduced to predict the air pressure distribution inside a cylindrical tablet under symmetric compaction. A nonlinear, transient 1D PDE has been solved numerically.
--
(3) One of the main mechanisms behind tablet lamination is excessive air entrapment. If the entrapped air pressure inside the tablet exceeds a certain threshold, the tablet often laminates along the horizontal centerline. While tensile strength must be measured experimentally, the maximum air pressure can be estimated. This is why I reproduced the results of this paper using numerical simulation.
--
(4) The code can predict air pressure as a function of punch velocity, permeability, vertical displacement, and punch–die gap.
---
