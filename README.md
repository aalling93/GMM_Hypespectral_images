# GMM on Hypespectral images
Gausian Mixture Models applied on Hyperspectral Satellite images to automatically extract vegetation, the sea and cities

-----------------------------------
# Hyperspectral imagery
Optical-, multi-, and hyper-spectral sensors are all measuring the intensity of electromagnetic waves reflected by a target's surface in each spectral band available to the sensor. These bands are often measuring reflections from the ultraviolet (100-400nm) to the near infrared (750-1400 nm) electromagnetic regions, and even to 2500nm. By comparing the measured spectral signature with the source incident spectra, it is possible to derive the physical and chemical properties of the target. Water, sea ice, chlorophyll, basalt rocks, diorite rocks  etc. have widely different spectra, meaning a distinction of not only the individual targets is possible, but also their conditions. Optical sensors measures the intensity in three bands; red, green and blue whereas multi-spectral sensors measures the intensity in tens of bands and hyper-spectral sensor in hundreds of bands. For instance, Chlorophyll has a high intensity in the near infrared(NIR) band and low intensity in the red band, whereas water has a high intensity in the blue band with low intensity in both red and NIR. It is consequently possible to distinguish between water with and without high concentrations of chlorophyll using a multi- or hyper-spectral sensor. Similartly, using e.g. a hyper/spectral sensor, it is possible to distinguish between different kinds of rocks, and even gold (if it is on the surface). The most common source of illumination is the sun, and when available, the sensors can measure a reflection in the entire optical spectrum.
<img src="figures/hyper1.PNG" width="400" height="400">


----------------------------------
# Unsupervised classification
