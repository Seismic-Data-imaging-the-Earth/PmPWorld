# The Moho-reflected PmP Wave
<p align="center">
  <img src="https://github.com/Seismic-Data-imaging-the-Earth/PmPWorld/blob/master/source/photos/PmPShow.png" />
</p>

---

### This site will host a series of materials and database about the Moho-reflected wave — PmP phase. 

At present, We have developed a **two-stage workflow** of identifying and picking PmP waves in a semiautomatic way ([**Li et al., 2022**](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)). Briefly speaking, the **two-stage workflow** includes two parts: At the first stage, high-quality PmP waves are automatically picked on selected seismograms. At the same time, a visual check on three-component waveforms is conducted to confirm that the chosen signals indeed come from Moho reflection. At the second stage, the volume of the PmP dataset is expanded by involving other waves traveling along similar paths as those picked at the first stage. By utilizing the newly developed **two-stage workflow**, we have built the first PmP database with 10,192 PmP waves from the broadband vertical-component seismic data retrieved from southern California Earthquake Data Center ([SCEDC](https://scedc.caltech.edu/)). 

By utilizing the high-quality PmP dataset (10,192 manual picks) in southern California, we further develop **PmPNet** ([**Ding et al., 2022**](https://doi.org/10.48550/arXiv.2112.07655)), a deep-neural-network-based algorithm to automatically identify PmP waves efficiently. **PmPNet** applies similar techniques in the machine learning community to address the unbalancement of PmP datasets. The trained optimal **PmPNet** can efficiently achieve high precision and high recall simultaneously to automatically identify PmP waves from a massive seismic database. Applying the pre-trained **PmPNet** to the seismic database from January 1990 to December 1999 in southern California, we obtain nearly twice more PmP picks than the original PmP dataset.

More detailed information on PmP database and our developed workflow/code to identify PmP phase can be found at [**PmPWorld**](https://pmpworld.readthedocs.io/en/latest/) documentation.


---

## Quick links

* [PmP database built by two-stage workflow](https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/HKCXBF) ([Li et al. 2022](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)).
* [PmP database built by PmPNet](https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/0O380V) ([Ding et al. 2022](https://doi.org/10.48550/arXiv.2112.07655)).
* Codes for PmPNet and PmP-traveltime-Net ([Ding et al. 2022](https://doi.org/10.48550/arXiv.2112.07655)).


---

## References

* [Li et al. 2022. Moho Complexity in Southern California Revealed by Local PmP and Teleseismic Ps Waves](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)

* [Ding et al. 2022. Deep Neural Networks for Creating Reliable PmP Database with a Case Study in Southern California](https://doi.org/10.48550/arXiv.2112.07655)


