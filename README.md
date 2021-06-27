# A hands-on introduction to Multiple Point Statistics

Gregoire Mariethoz, Mathieu Gravey, Fabio Oriani



Recommended for: geoscientists, climate scientists, geostatisticians, engineers.

This course is an introduction to stochastic simulation using Multiple Point Statistics (MPS), a modelling approach based on the use of training images with the aim of generating realistic heterogeneity characterizing natural processes. This family of techniques has been shown to be particularly suited for representing complex spatial/temporal features, for example the connectivity and geometry of geological units [1], the seasonality and complex time dependence of climate time-series [2], or the small-scale variability of missing data from remote sensing images [3].

In the routine practice, MPS can be used to fill the gaps in spatial or temporal datasets, interpolate sparse data, or simulate random fields to study the uncertainty of a process outcome. We will present the theory behind MPS, demonstrate an open-source code, and give practical tutorials on how to use it.

The course will be organized in two parts: the first one is a short introduction on the theory underlying stochastic simulation and interpolation. The second and main part is dedicated to practical cases related to time series modeling and remote sensing data. The QS algorithm will be used [4], available here: https://gaia-unil.github.io/G2S/. For simplicity, the workshop will be held online using the free resource from Google Collaboratory, for which you will only need a Google account (it can be done even with non-google email addresses, https://accounts.google.com/).

This repository contains the powerpoint presentation of the first part, and a Colab notebook for part 2. The colab notebook can be accessed directly using the link above.

References:

[1] dell’Arciprete, D., Bersezio, R., Felletti, F. et al., Comparison of three geostatistical methods for hydrofacies simulation: a test on alluvial sediments, Hydrogeol Journal (2012) 20: 299. https://doi.org/10.1007/s10040-011-0808-0

[2] Oriani F, Mehrotra R, Mariethoz G, Straubhaar J, Sharma A, Renard P (2017). Simulating rainfall time-series: how to account for statistical variability at multiple scales, Stochastic Environmental Research and Risk Assessment, doi: 10.1007/s00477-017-1414-z.

[3] Gaohong Yin, Gregoire Mariethoz, Ying Sun & Matthew F. McCabe (2017) A comparison of gap-filling approaches for Landsat-7 satellite data, International Journal of Remote Sensing, 38:23, 6653-6679, DOI: 10.1080/01431161.2017.1363432

[4] Gravey, M., & Mariethoz, G. (2020). QuickSampling v1.0: a robust and simplified pixel-based multiple-point simulation approach. Geoscientific Model Development, 13(6), 2611–2630. https://doi.org/10.5194/gmd-13-2611-2020.


