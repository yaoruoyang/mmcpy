## Mesh-based Monte Carlo in Python
Mesh-based Monte Carlo (MMC) is a powerful photon simulator proposed by Dr. Qianqian Fang at Northeastern University. 
The repository can be found at https://github.com/fangq/mmc and a stable release can be downloaded from http://mcx.space/#mmc.

At least 5 papers related to the MMC project have been published so far, including:
* [Mesh-based Monte Carlo method using fast ray-tracing in Plücker coordinates (2010)](https://www.osapublishing.org/boe/abstract.cfm?uri=boe-1-1-165)
* [Accelerating mesh-based Monte Carlo method on modern CPU architectures (2012)](https://www.osapublishing.org/boe/abstract.cfm?uri=boe-3-12-3223)
* [Mesh-based Monte Carlo method in time-domain widefield fluorescence molecular tomography (2012)](https://www.spiedigitallibrary.org/journals/Journal-of-Biomedical-Optics/volume-17/issue-10/106009/Mesh-based-Monte-Carlo-method-in-time-domain-widefield-fluorescence/10.1117/1.JBO.17.10.106009.short?SSO=1)
* [Generalized mesh-based Monte Carlo for wide-field illumination and detection via mesh retessellation (2015)](https://www.osapublishing.org/boe/abstract.cfm?uri=boe-7-1-171)
* [Direct approach to compute Jacobians for diffuse optical tomography using perturbation Monte Carlo-based photon “replay” (2018)](https://www.osapublishing.org/boe/abstract.cfm?uri=boe-9-10-4588)

I started working on MMC with Dr.Fang from 2013 when I started my PhD and publish two papers on it as first author. Currently MMC is written in C, with some C++ codes supporting MMCLAB, and some utility codes in MATLAB. I came up with this idea of rewriting MMC in Python to:
* Improve my own Python programming skills; 
* Make MMC available to more people as Python gains more popularity; 
* Reorganize MMC in a more modular fashion so it can be easily maintained and extended in the future.
