Phase Identification
====================

PmP features
------------

Previous studies have summarized the following criteria to identify PmP waves:

*  PmP waves are usually prominent on seismic waveforms of local shallow crustal earthquakes (e.g., with epicentral distance from 50
   to 200 km and focal depth shallower than 20 km in southern California; `Richards-Dinger & Shearer. 1997 <https://doi.org/10.1029/97jb00883>`_);

*  The amplitude of the PmP wave is large and sometimes larger than that of the first P, especially at postcritical
   epicentral distances (e.g., >70 or 80 km in the `IASP91 model <https://doi.org/10.1111/j.1365-246x.1991.tb06724.x>`_;
   `Bormann et al. 2012 <https://gfzpublic.gfz-potsdam.de/pubman/faces/ViewItemOverviewPage.jsp?itemId=item_65558>`_;
   `Nakajima et al., 2002 <https://doi.org/10.1016/s0031-9201(01)00307-7>`_);

*  Particle motions of the PmP and P waves are similar to each other, as both are compressional
   waves (`Nakajima et al. 2002 <https://doi.org/10.1016/s0031-9201(01)00307-7>`_).

The process of picking PmP waves can be simplified and performed in an automatic manner if we further consider:

*  There usually exists a low-amplitude zone between the P and PmP waves.

The reliability of the picked PmP waves can be enhanced if we additionally consider:

*  Once there is a visible PmP wave from the Moho interface, it is highly possible that the SmS
   wave can be observed simultaneously (`Nakajima et al. 2002 <https://doi.org/10.1016/s0031-9201(01)00307-7>`_).

Two-Stage Workflow
------------------

At the first stage:

*   First, aligning the vertical-component waveforms with P-wave signal-to-noise ratio greater
    than 10 at the observed first P-wave arrivals.

.. figure:: /photos/PmPick_TSW1.png
   :alt: Align First P.
   :width: 30.0%
   :align: center

*  Second, automatically searching for the PmP waves based on the PmP-P differential travel time using a series of modified
   HK models. Waveform envelopes with a strong signal in the PmP window (in black), and a low-amplitude zone (in orange)
   between the P (in blue) and PmP windows are selected.

.. figure:: /photos/PmPick_TSW2.png
  :alt: Automatically Search for PmP Waves.
  :width: 60.0%
  :align: center

*  Third, retaining only those three-component waveforms with identifiable P, PmP, S, and SmS arrivals indicated by the
   color-coded vertical lines.

.. figure:: /photos/PmPick_TSW3.png
 :alt: Visually Check the Co-existence of P, PmP, S and SmS phases.
 :width: 60.0%
 :align: center

At the second stage:

*  Expanding the volume of the PmP waves picked in Stage I by assembling all the downloaded vertical-component waveforms
   with P-wave signal-to-noise ratio greater than 3 into common reflection gathers.

.. figure:: /photos/PmPick_TSW4.png
  :alt: Expand the Data Volumn of PmP Waves.
  :width: 100.0%
  :align: center

  One example gather. Each gather contains only one stage-I reference waveform (top purple trace). Earthquake depth (evdp),
  event-station distance (dist), and event ID (EvtID) are also listed for each trace. The waveform similarity (CC) between the only
  stage-I waveform and every other waveform in the same gather is checked (>0.7).
