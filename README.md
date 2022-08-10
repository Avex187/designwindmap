# Undergraduate Thesis - Design Wind Map for Western Java, Indonesia
This repository contains all supplementary code that were used in the undergraduate thesis: <br /> <br />

"Wind Map Modeling for West Java Region and Analysis with Indonesian Disaster Map"

by Hafidz Rizky Firmansyah, Bandung Institute of Technology, Indonesia, 2021

Faculty of Civil and Environmental Engineering, Civil Engineering Department <br /> <br />

The comprehensive results of this study were published in International Journal of Disaster Risk Science (IJDRS), 2022, with the authors of:

Abdillah, M.R., Sarli, P.W., Firmansyah, H.R. et al. Extreme Wind Variability and Wind Map Development in Western Java, Indonesia. Int J Disaster Risk Sci 13, 465–480 (2022). https://doi.org/10.1007/s13753-022-00420-7

## Raw Data
### Raw Data are available upon request
Contacts : hafidz.rizky@outlook.com

# Abstract
Strong winds are one of the most common disasters in Indonesia. Not only do they affect houses which are generally classified as non-engineered structures, structures specifically designed according to design standards such as the Arcamanik Stadium in Bandung and the LRT station in Serpong, Tangerang are also not spared from damage due to strong winds. The building design codes that is often used in Indonesia has been quite good in modeling the behavior of structures that experience wind loads. However, for the aspect of applied wind magnitude, there is some room for improvement.

Indonesian building design standards, such as PPPURG 1987, SNI 1727-2013, and SNI 1725-2016 which regulate loading on structures, have not considered the geographical location of the building and the wind return period in determining the design speed. Foreign building standards such as HB 212-2002 from Australia, have considered the return period but assumes Indonesia as a region with homogeneous characteristics. It is quite difficult to accept the statement that a country with an area of 1.9 million km2 has the same weather characteristics.

Therefore, this final project aims to map the wind magnitude with a certain return period in Indonesia with a focus on the West Java region. This wind return period becomes very important as the basis for the design of structures that have a service life of the building and experience the possibility of receiving these extreme wind loads during their service life.

Although the data on wind observation stations in Indonesia is limited and only a small part meets the criteria for a reliable observation station, current technological capabilities allow software to continuously estimate weather parameters, namely ERA5. To ensure that the bias of this device can be minimized, observation data is needed to calibrate the existing ERA5 simulation results.

After obtaining this calibrated annual maximum wind value, the most suitable distribution to describe the distribution of this extreme value is evaluated. The Gumbel extreme distribution which has been validated by testing the distribution suitability in the high and lowland locations in the West Java region is used.

After the Gumbel distribution model was proven to be applicable for the entire West Java region, various analytical methods were used to estimate the design wind speed parameters with various return periods at the locations specified. The analytical method used is the graphical method, MOM, and LMOM. From these various analytical methods, a method is sought that produces wind maps that have the smallest RMSE value. Based on the comparison between the results of Gumbel's parameter calculations, it is concluded that the LMOM method is used for 2 main reasons: (1) it has the smallest RMSE value in the majority of the calculated grid and (2) it has the maximum error value which is lower than the maximum error of the other 2 methods.

The hypothesis in this final project is the area with a large number of incidents of damage due to high wind disasters, has a wind magnitude value that is relatively larger than other areas, with the same return period. This damage incident data was obtained from the Indonesian National Board of Disaster Management. However, because this disaster data is multiple disaster report from a location that experienced an wind incident, the nature of this disaster data is very dependent on the population density in the area, so the value of the population density in an area must be considered as a factor that affects the number of disaster reports, which are carried out by normalizing disaster maps with population density maps. The normalized disaster map is compared with the wind map and has a good resemblance; The extreme points where multiple incidents occur is the point with the high design wind speed on the wind map.

After the LMOM analytical method is obtained and produces a wind map that has the smallest RMSE, this calculation can be applied to all regions in Indonesia to produce a comprehensive wind map with various return periods for the purposes of risk-based building design and building service life.

Keywords: Wind Map, Return Period, Gumbel Distribution, Risk Based Design,  ERA5, Analytical Method

## Design Wind Map Results for Western Java, Indonesia (m/s)
![alt text](https://github.com/hafidzrf/designwindmap/blob/main/images/wind_maps.webp)
