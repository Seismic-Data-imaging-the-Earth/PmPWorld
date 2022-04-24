Machine Learning
====================

By utilizing the high-quality PmP dataset (10,192 manual picks by `Li et al., 2022 <https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033>`_) in southern California,
we further develop **PmPNet** (`Ding et al., 2022 <https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023830>`_), a deep-neural-network-based algorithm to automatically
identify PmP waves efficiently. **PmPNet** applies similar techniques in the machine learning community to address the unbalancement
of PmP datasets. The trained optimal **PmPNet** can efficiently achieve high precision and high recall simultaneously to automatically
identify PmP waves from a massive seismic database.

.. figure:: /photos/PmPNet_Trainflow.png
   :alt: Training flow of PmPNet.
   :width: 100.0%
   :align: center

   PmPNet training flow: (i) one batch of data points is fed into **PmPNet**, and the loss between the **PmPNet** output and the true
   labels is computed; and (ii) the optimizer reads in the loss and update the trainable parameters of **PmPNet**. One epoch of
   training consists of continuing this iteration until the whole dataset has been tranversed. The training phase for **PmPNet**
   is complete when the pre-selected maximum number of epochs is reached.

.. toctree::
  :maxdepth: 1

  Algorithm
  PmPNet
  PmP-traveltime-Net
