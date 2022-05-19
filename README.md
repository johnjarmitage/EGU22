# EGU presentation as a notebook

This a repo with a notebook used to make the hopefully less than 7 minute presentation I gave at [EGU22](https://www.egu22.eu/):

## EGU22-2826 | Presentations | GM3.1 | Highlight  

[**Modelling sediment yield in an elementary catchment: reducing the complexity to the key processes**](https://meetingorganizer.copernicus.org/EGU22/EGU22-2826.html)

*John Armitage, Nolwen Venisse, Christine Franke, Claire Alary, and Morgan Delaporte*

The transport of sediment within a catchment is a complex interaction between the physics of granular transport and the intrinsic local conditions of the sedimentary basin. In trying to understand the causal relationship between climate and sediment transport within a process-based numerical model, the system needs to be simplified. At one extreme at geological timescales there are simple diffusion or advection-based models of transport with only a handful of parameters. At the other extreme complex land surface models for weather forecasting rely on a multitude of user defined parameters. In geomorphology we are faced with the challenge of scale – at what spatial and temporal scale are events important – combined with the uncertainty of various processes and the associated parameters. If we wish to forecast future sustainability for land use over the next 20 to 100 years (including soil loss), the problems of scale and unknown parameters becomes acute. To enter this problem, we have explored the potential of the process-based CAESAR-Lisflood (C++ version) model to simulate the observed erosion of a small sub-catchment within the upper Canche River watershed in the Haut-De-France region. The Pommeroye catchment is of a scale of 0.5 km2, it is composed of 14 cultivated fields and has had continuous monitoring of sediment yield for two years. We focus on using CAESAR-Lisflood as a platform to explore (1) what spatial and temporal scale and (2) what processes are required to match the observed relation between rainfall and sediment yield. We find that a relatively simple model with a 30 cm transport-limited top-soil layer above a detachment-limited layer can match the magnitude of sediment yield. In our set-up the model has only three unconstrained parameters that we tune to give a better fit to the observations: an infiltration parameter that controls peak run-off and the recession curve, a Manning’s roughness within the water routing algorithm, and the erodibility for the detachment-limited law. However, this reduced complexity model cannot capture the ephemeral nature of the landscape, where only certain rainfall events lead to significant sediment yield. A key uncertainty is infiltration and groundwater flow. The transition from precipitation to run-off is calculated by a local recession curve assuming storage at each model cell. However, within the study catchment groundwater pathways cannot be ignored, and it is only when the soil is saturated or when rainfall exceeds the infiltration rate that significant sediment transport occurs. We would therefore suggest that future efforts should be focused on understanding the relationship between the water flux at surface and in the sub-surface to understand how precipitation is translated into sediment flux.

## Launch the notebook in [mybinder](https://mybinder.org/)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/johnjarmitage/EGU22/HEAD?labpath=presentation.ipynb)

Hit the `voila` button to make it pretty.

## Get more detail in curve.space

Checkout this repo as a [webpage](https://jarmitage.curve.space/)
