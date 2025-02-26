# The Moho-reflected PmP Wave
<p align="center">
  <img src="https://github.com/Seismic-Data-imaging-the-Earth/PmPWorld/blob/master/source/photos/PmPShow.png" />
</p>

---

### This site will host a series of materials and database about the Moho-reflected wave — PmP phase. 

At present, We have developed a **two-stage workflow** of identifying and picking PmP waves in a semiautomatic way ([**Li et al., 2022**](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)). Briefly speaking, the **two-stage workflow** includes two parts: At the first stage, high-quality PmP waves are automatically picked on selected seismograms. At the same time, a visual check on three-component waveforms is conducted to confirm that the chosen signals indeed come from Moho reflection. At the second stage, the volume of the PmP dataset is expanded by involving other waves traveling along similar paths as those picked at the first stage. By utilizing the newly developed **two-stage workflow**, we have built the first PmP database with 10,192 PmP waves from the broadband vertical-component seismic data (from January 2000 to December 2018) retrieved from southern California Earthquake Data Center ([SCEDC](https://scedc.caltech.edu/)). 

By utilizing the high-quality PmP dataset (10,192 manual picks) in southern California, we further develop **PmPNet** ([**Ding et al., 2022**](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023830)), a deep-neural-network-based algorithm to automatically identify PmP waves efficiently. **PmPNet** applies similar techniques in the machine learning community to address the unbalancement of PmP datasets. The trained optimal **PmPNet** can efficiently achieve high precision and high recall simultaneously to automatically identify PmP waves from a massive seismic database. Applying the pre-trained **PmPNet** to the seismic database from January 1990 to December 1999 in southern California, we obtain nearly twice more PmP picks than the original PmP dataset.

More detailed information on PmP database and our developed workflow/code to identify PmP phase can be found at [**PmPWorld**](https://pmpworld.readthedocs.io/en/latest/index.html) documentation.


---

## Quick links

#### Methodologies

* [PmP database built by two-stage workflow](https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/HKCXBF) ([Li et al. 2022](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)).
* PmP database built by the updated two-stage workflow (in preparation).
* [PmP database built by PmPNet](https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/0O380V) ([Ding et al. 2022](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023830)).
* [Codes for PmPNet and PmP-traveltime-Net](https://zenodo.org/record/6499773#.YmuvHnVByJA) ([Ding et al. 2022](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023830)).
* [Example data for PmPNet and PmP-traveltime-Net](https://osf.io/haxg8/).

#### Applications

##### $\Rrightarrow$ Moho geometries

* [Southern California](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)
* [Northern California](https://www.pnas.org/doi/abs/10.1073/pnas.2317809121)

##### $\Rrightarrow$ Deep volcanic architectures

* [Coso volcanic field in Southern California](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023582)
* [Clear Lake volcanic field in Northern California](https://www.pnas.org/doi/abs/10.1073/pnas.2317809121)

##### $\Rrightarrow$ Deep fault root

* [Parkfield region, California](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2024JB029918)

##### $\Rrightarrow$ Deep seismogenic structures

* [Southern California](https://www.sciencedirect.com/science/article/pii/S0040195122001226)

#### Databases

* [Southern California](https://doi.org/10.21979/N9/HKCXBF)
* [Northern California](https://doi.org/10.21979/N9/JPCTF9)
* Long Valley caldera region (in preparation)


---

## References

* [Chen, G., Chen, J., Li, T., Xu, M., Zhao, Q., & Tong, P. (2025). Adjoint‐state reflection traveltime tomography for velocity and interface inversion with its application in central California near Parkfield. Journal of Geophysical Research: Solid Earth, 130(1), e2024JB029918.](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2024JB029918)

* [Li, T., Wu, S., & Tong, P. (2024). Multilevel transcrustal magmatic system beneath the Geysers-Clear Lake area. Proceedings of the National Academy of Sciences, 121(12), e2317809121.](https://www.pnas.org/doi/abs/10.1073/pnas.2317809121)

* [Wu, Shucheng, et al. "Lower crust structures and dynamics of southern California revealed by first P and PmP traveltime data." Tectonophysics 830 (2022): 229328.](https://www.sciencedirect.com/science/article/pii/S0040195122001226)

* [Wang, D., Wu, S., Li, T., Tong, P., & Gao, Y. (2022). Elongated magma plumbing system beneath the Coso volcanic field, California, constrained by seismic reflection tomography. Journal of Geophysical Research: Solid Earth, 127(6), e2021JB023582.](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023582)

* [Ding, W., Li, T., Yang, X., Ren, K., & Tong, P. (2022). Deep neural networks for creating reliable PmP database with a case study in southern California. Journal of Geophysical Research: Solid Earth, 127(4), e2021JB023830.](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023830)

* [Li, T., Yao, J., Wu, S., Xu, M., & Tong, P. (2022). Moho complexity in southern California revealed by local PmP and teleseismic Ps waves. Journal of Geophysical Research: Solid Earth, 127(2), e2021JB023033.](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)
