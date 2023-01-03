# Active-contours-driven-by-local-Gaussian-distribution
Active contours driven by local Gaussian distribution
This Matlab code implements a segmentation method using local Gaussian distribution fitting energy, 
proposed by Li Wang et al's in the paper "Active Contours Driven by Local Gaussian Distribution Fitting Energy. Signal Processing, 89(12), 2009, p. 2435-2447" http://www.sciencedirect.com/science/article/pii/S0165168409000942 
The local image intensities are described by Gaussian distributions with different means and variances. The energy minimization is achieved by an interleaved level set evolution and estimation of local intensity means and variances in an iterative process. The means and variances of local intensities are considered as spatially varying functions to handle intensity inhomogeneities and noise of spatially varying strength. 
![Local_Gaussian_Fitting](https://user-images.githubusercontent.com/64495436/210386633-f628ec98-5cd9-4c7b-8ce9-14319992ea34.jpg)

Source code: [LGD_source_code.zip](https://github.com/DBC-Lab/Active-contours-driven-by-local-Gaussian-distribution/files/10337706/LGD_source_code.zip)
