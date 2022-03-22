Southern California
===================

PmP Database by Two-Stage Workflow
----------------------------------

By utilizing the newly developed two-stage workflow (`Li et al., 2002 <https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033>`_),
we have built the `first PmP database with 10,192 PmP waves <https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/HKCXBF>`_
from the broadband vertical-component seismic data (from January 2000
to December 2018) retrieved from southern California Earthquake Data Center (`SCEDC <https://scedc.caltech.edu>`_).


PmP Database by PmPNet
----------------------

Applying the pre-trained PmPNet (`Ding et al., 2002 <https://doi.org/10.48550/arXiv.2112.07655>`_) to the seismic database from
January 1990 to December 2018 in southern California, we update the `PmP database with 28,093 picks <https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/0O380V>`_.

Example of the PmP waves recorded at the short-period station CI.BRG and broadband station AZ.SND:

.. figure:: /photos/PmPNet_Data1.png
   :alt: Example of PmP Waveforms.
   :width: 100.0%
   :align: center

   In the map, the seismic station is denoted as the black-filled square, and local earthquakes are represented as the red-filled stars.
   For the PmP waveforms, they have been aligned to the first P-wave arrivals and normalized in the displaying window.
   The onset time for the PmP wave is indicated by the red bar. Numbers in purple show the earthquake depth (evdp) and the
   event-station distance (dist) for each waveform.

Data coverage of PmP database and direct inference about Moho geometry beneath southern California:

.. figure:: /photos/PmPNet_Data2.png
   :alt: Data Coverage of PmP Database
   :width: 100.0%
   :align: center

   The number of PmP reflection points counted at each node of a 30 km by 30 km grid. The Moho geometry estimated from the new PmP
   database at every node of the same grid. The Moho depth is the average over a reflection gather, assuming a constant Vp = 6.3 km/s.
   The Moho geometry compiled in California Moho Model version 1.0 (CMM-1.0, `Tape et al. 2012 <https://doi.org/10.1785/0220110118>`_), which is built mainly based on teleseismic Ps data and
   active-source surveys.
