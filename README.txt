This QGIS plugin allows the user to track the spread of the COVID19 across the globe in realtime. The plugin gives the user 3 options:

-Track number of cases
-Track number of Deaths
-Track number Death Probability

By Death Probability is meant to divide the number of deaths by the number of cases for a given station, and multiplying by 100.  

The data is taken from GitHub, from the following database:
https://github.com/CSSEGISandData/COVID-19

This database uses data from:
-World Health Organization (WHO): https://www.who.int/
-DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia.
-BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/
-National Health Commission of the People’s Republic of China (NHC):
 http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml
-China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm
-Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html
-Macau Government: https://www.ssm.gov.mo/portal/
-Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0
-US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html
-Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html
-Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance
-European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases
-Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19
-Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus

This plugin was developed and so far tested on QGIS3.10 and QGIS3.4.  
The plugin requires the following python modules to be installed: 

-pandas
-requests
-numpy
-os

This Plugin is developed by Pawel Dzierzynski from The Map Workshop
Contact me for more information: themapworkshop@gmail.com  
© 2020 The Map Workshop
