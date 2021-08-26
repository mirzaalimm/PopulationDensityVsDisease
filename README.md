# Population Density vs Disease
This repository contains the resources (raw data and processed data) of our paper*: \
M. A. Mutasodirin, R. D. Rizqullah, A. Setiyoko, and A. M. Arymurthy, *"Settlement Mapping for Population Density Modelling in Disease Risk Spatial Analysis"*, 2021. \
\*Under consideration for presentation at The 6th International Workshop on Big Data and Information Security (IWBIS) 2021.

# Abstract
In disease risk spatial analysis, many researchers especially in Indonesia are still modelling population density as the ratio of total population to administrative area extent. This model oversimplifies the problem, because it covers large uninhabited areas, while the model should focus on inhabited areas. This study uses settlement mapping against satellite imagery to focus the model and calculate settlement area extent. As far as our search goes, we did not find any specific studies comparing the use of settlement mapping with administrative area to model population density in computing its correlation to a disease case rate. This study investigates the comparison of both models using data on Tuberculosis (TB) case rate in Central and East Java Indonesia. Our study shows that using administrative area density the Spearman's rho was considered as "Fair" (0.566, p<0.01) and using settlement density was "Moderately Strong" (0.685, p<0.01). The difference is significant according to Hotelling's t test. By this result we are encouraging researchers to use settlement mapping to improve population density modelling in disease risk spatial analysis. Resources used and resulted by this work are publicly available at https://github.com/mirzaalimm/PopulationDensityVsDisease.

# Keywords
population density, settlement density, settlement map, disease risk, indonesia.

# Data
Administratif Boundary: \
(BIG | accessed:2021) https://portal.ina-sdi.or.id/downloadaoi/ \
\
Administratif Area Extent: \
(BPS | accessed:2021) https://jateng.bps.go.id/indicator/153/613/1/luas-wilayah-menurut-kabupaten-kota.html \
(BPS | accessed:2021) https://jatim.bps.go.id/statictable/2019/10/11/1823/luas-wilayah-menurut-kabupaten-kota-di-provinsi-jawa-timur-2017.html \
\
Number of Population: \
(BPS | accessed:2021) https://jateng.bps.go.id/indicator/12/766/1/jumlah-penduduk-menurut-kabupaten-kota-di-jawa-tengah.html \
(BPS | accessed:2021) https://jatim.bps.go.id/indicator/12/375/1/jumlah-penduduk-provinsi-jawa-timur.html \
\
Disease Incidence and Rate: \
(BPS | accessed:2021) https://jateng.bps.go.id/statictable/2020/07/20/1875/jumlah-kasus-penyakit-menurut-kabupaten-kota-dan-jenis-penyakit-di-provinsi-jawa-tengah-2019.html \
(BPS | accessed:2021) https://jatim.bps.go.id/statictable/2019/10/09/1674/jumlah-kasus-penyakit-menurut-kabupaten-kota-dan-jenis-penyakit-di-provinsi-jawa-timur-2018-.html \
\
Settlement Map: \
(EC | accessed:2021) https://ghsl.jrc.ec.europa.eu/download.php?ds=buS2

# Processed Data
[Satellite Imagery of Central Java](https://drive.google.com/drive/folders/1h-SadcASXQpMA1bZJn9WcIp_Vagn0hy-?usp=sharing) \
[Satellite Imagery of East Java](https://drive.google.com/drive/folders/10rZDnDeag89sAxfC45GBHZv020hjsukk?usp=sharing) \
[Settlement Map of Central Java](https://drive.google.com/drive/folders/1sn5Z0CZJEAwSNu4rX48l_5os4GtKnd5X?usp=sharing) \
[Settlement Map of East Java](https://drive.google.com/drive/folders/1vEiK3WdocpL39xLpLHkuAAN7_fTEOhq0?usp=sharing) \
\
[Correlation Calculation of Central Java](https://docs.google.com/spreadsheets/d/1vXJYdGS_VkDr-l-aVLR8klwmHu66geeJkUEain9LybU/edit?usp=sharing) \
[Correlation Calculation of East Java](https://docs.google.com/spreadsheets/d/1Ohxnv8PwgMb_r2fc1zwS5nGZNZUghU5QcNq0STtOrzc/edit?usp=sharing) \
[Correlation Calculation of Central+East Java](https://docs.google.com/spreadsheets/d/1Bva8yi-AfyBZLCyJ_S8Gyq0RGv4BCN8I0OV-XMaknLo/edit?usp=sharing) \
\
Note: In our study, we only processed two provinces. We may give more provinces of Java island later, in this repository, to help people conducting research. Feel free to contact me via email: mirza.alim.m@gmail.com.

# License
MIT
