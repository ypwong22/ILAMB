ILAMB 2.5 with Soil Moisture Functionalities
=================

This software is branched from version 2.5 of the International 
Land Model Benchmarking (`ILAMB <https://github.com/rubisco-sfa/ILAMB>`_) package. 
It adds a soil moisture evaluation subroutine (`ConfSoilMoisture.py`) featuring 

* layerwise evaluation of model performance on soil moisture (new)

* the use of a merged global `dataset <https://essd.copernicus.org/articles/13/4385/2021/essd-13-4385-2021.html>`_ that outperforms individual sources (new)

The metrics include: 

* climatology, seasonality, and spatial relationships (standard)

* grid-wise temporal trends based on user-specified time window (new)

* grid-wise partial correlation between soil moisture and any other user-specified 
  variables (e.g. precipitation, temperature, leaf area index, evapotranspiration, ...) (new)

The additions are integrated into the standard ILAMB v2.5 visualization and scoring workflow. 

Checkout also
------------------

* The ILAMB `website <https://www.ilamb.org>`_
* The ongoing `evaluation <https://www.ilamb.org/dev/SoilMoisture/>`_ on CMIP6 soil moisture-biogeochemistry feedbacks
* The RUBISCO `Soil Moisture Working Group <https://docs.google.com/forms/d/e/1FAIpQLScxGzL_58N2iIHgEH9pn3me4sHC2gUlBfqVgCuhD0D3-n8sSA/viewform>`_

Funding
-------

This research was performed for the *Reducing Uncertainties in Biogeochemical Interactions through Synthesis and Computation* (RUBISCO) Scientific Focus Area, which is sponsored by the Regional and Global Climate Modeling (RGCM) Program in the Climate and Environmental Sciences Division (CESD) of the Biological and Environmental Research (BER) Program in the U.S. Department of Energy Office of Science.
