The following files are part of the Taranaki Basin Curated Well Logs Dataset hosted on IBM Developer Data Asset eXchange.

Homepage: https://developer.ibm.com/exchanges/data/all/taranaki-basin-curated-well-logs-data/

File list: 
-- coords.csv : This data file provides the coordinates of the wells.
-- logs.csv : This data file provides the well logs information.
-- LICENSE.txt : a plaintext version of the CLDA-Sharing license that the dataset is licensed under. (https://cdla.io/sharing-1-0/)

The data was curated from two sources, the New Zealand Petroleum & Minerals Online Exploration Database (data.nzpam.govt.nz), and the Petlab (pet.gns.cri.nz), which served to characterize the Taranaki basin. In particular, the data served to map important tectonic regions in the basin and the various formations in these regions. We used geological reports to identify formation markers, spreadsheets to find well header and drilling deviation information, and finally, LAS files to characterize a reasonable set of well log annotations. The curated dataset consists of a set with 407 wells containing the main geophysical well logs and reported geological formations in true vertical depth.

The Taranaki basin comprises an area of about 330.000 km2, located broadly onshore and offshore the New Zealand west coast. This basin is the main exploratory and productive region of New Zealand, with over 400 wells drilled to date. The basin consists of sedimentary rocks dated from Late Cretaceous to present, covering the Paleozoic and Mesozoic basement rocks. 

The data were then prepared, processed and cleaned from various files into a final CSV format including the well logs, the coordinates of the wells, and the corresponding labels. 

The fields of `logs.csv` file are explained below:
BS:   (float) Bit size
GR:   (float) Gamma Ray
NEUT: (float) Neutron
DENS: (float) Density
SP:   (float) Spontaneous potential
PEF:  (float) Photoelectric effect
DTC:  (float) Compressional Slowness
DRHO: (float) Density-porosity
RESD: (float) Resistivity deep
RESS: (float) Resistivity shallow
RESM: (float) Resistivity medium
CALI: (float) Caliper
TENS: (float) Tension
TEMP: (float) Temperature
DEPT: (float) Depth of the data point measured along the well
ONSHORE: (bool) boolean value indicating if the data point belongs to an onshore well (if not, it belongs to an offshore well)
DIRSURVEY: (bool) boolean value indicating if there were any directional survey available to infer the correct position of this data point
WELLNAME: (str) name of the well containing the given data point


