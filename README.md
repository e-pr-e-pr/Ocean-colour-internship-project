The packages you will need to run these scripts are:
- numpy
- pandas
- matplotlib.pyplot
- datetime

I used python version 3.12.2 , and conda version 24.1.2. You can also use the environment.yml here to get the same environments. 

The data, particularly for the in-situ data, is available by request.

The sentinel-3 and sentinel-2 data can be downlaoded here: 
https://data.eumetsat.int/search?query=
https://dataspace.copernicus.eu/

For most of the plots, I used level 2 (atmospehric correction applied) data. Only for the atmospheric correction tests did I used level 1 data. 
However, there is nopython code for this, since it is done in SNAP, or via the acolite command line (https://github.com/acolite/acolite/tree/main/config)
