Imaging Power
==============

**1. Raypath comparison between first P and PmP waves:**

.. figure:: /photos/PmP_raypath.jpg
   :alt: Raypath comparison between first P and PmP waves.
   :width: 100.0%
   :align: center

   In the figure, the open stars denote sources, and the inverted filled triangles represent receivers. 
   Lime bold curve delineates the Moho interface. Blue curves denote synthetic first-P raypaths, 
   wherereas red curves denote synthetic PmP raypaths. Both synthetic raypaths are computed by solving the eikonal equation using `Pykonal <https://malcolmw.github.io/pykonal-docs/>`_ package 
   (`White et al., 2020 <https://doi.org/10.1785/0220190318/>`_).

On the one hand, we observe that the small-distance first P waves (Pg) sample the upper crust well, and the large-distance
first P waves (Pn) sample the uppermost mantle well. On the other hand, the PmP waves well sample the lower crust,
and thus can provide complementary constraints on the deep crustal structures.


**2. Slowness sensitivity kernel comparison between first P and PmP waves:**

.. figure:: /photos/phase_kernel.jpg
   :alt: Slowness sensitivity kernel comparison between first P and PmP waves.
   :width: 100.0%
   :align: center

   In the figure, the upper pannel shows the checkerboard model, and the black dashed curve delineates the Moho interface. 
   The middle pannel shows the slowness sensitivity kernel for the first P waves, and the lower pannel shows the slowness 
   sensitivity kernel for the PmP waves. Both phase sensitivity kernels are computed by solving the adjoint equation using `RefATT <https://refatt-docs.vercel.app/>`_ package 
   (`Chen et al., 2025 <https://doi.org/10.1029/2024JB029918/>`_).

