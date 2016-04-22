
# Open Power System Data: Power Plants in European countries

## About this Notebook

This is a ipython notebook that processes data on power plant capacities for European countries. The data includes generation capacity, generation technology, and locational information of individual power plants in European countries.

The final output of the notebook is a list of power plants and their technical specifications.

## Data sources

The data sources are mostly national sources on generation capacites. Some countries already provide detailed lists of national generation units including additional information on their locational and technical specifics. 

At the moment, only directly available lists are taken into account for the following countries:
- [[Germany](https://github.com/Open-Power-System-Data/datapackage_power_plants): Germany is currently addressed separately in the respective Github repository.]
- [Belgium](http://publications.elia.be/upload/ProductionParkOverview.xls?TS=20120416193815)
- [Finland](http://www.energiavirasto.fi/documents/10191/0/Energiaviraston+Voimalaitosrekisteri+040316.xlsx)
- [France](http://clients.rte-france.com/servlets/CodesEICServlet)
- [Italy](http://download.terna.it/terna/0000/0216/16.XLSX)
- [Poland](http://gpi.tge.pl/en/wykaz-jednostek?p_p_id=powerunits_WAR_powerunitsportlet&p_p_lifecycle=2&p_p_state=normal&p_p_mode=view&p_p_cacheability=cacheLevelPage&p_p_col_id=column-1&p_p_col_count=1)
- [Spain](http://www6.mityc.es/aplicaciones/electra/ElectraExp.csv.zip)
- [The Netherlands](http://www.tennet.org/english/operational_management/export_data.aspx)
- [UK](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/446457/dukes5_10.xls)

In the future, a further extension to other European countries is envisaged, as well as an extension of the current information by additional sources. These might include information on technical specifics as well as locational information for individual power plants.

## Links to Notebooks

The following notebooks are used to downlad and process the input data:
- [download and process](https://github.com/Open-Power-System-Data/datapackage_power_plants_europe/blob/master/download_and_process.ipynb)
- validate
   
