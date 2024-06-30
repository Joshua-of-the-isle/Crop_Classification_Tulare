Two raw sources of data were used for the project:

<b>The CDWR cropping data for Water year 2020<b>
This contained information about the crops grown in each field and the exact field boundaries, it was obtained in geopackage form.
It was not uploaded since the size of the geopackage was too large, however it can be acessed by simply visiting the cdwr website,
it was used along with the satellite imagery in order to extrct the spectral values of each field in qgis.

<b>The LANDSAT ARD data<b>
LANSAT imagery from eight periods in the year 2020 were taken, they were selected so that minimum cloud coverage was ensured. Various
types of data products are provided by NASA however we decided to use ARD data because it was the most convenient data form to work 
with, this data was then calculated at the field level and then stored in a postgresql database where it was further processed, it was then exported to a csv and then the data conatined in the csv was used for the classification task.
