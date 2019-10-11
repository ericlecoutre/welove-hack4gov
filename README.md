# welove-hack4gov
Repository for hack4gov BD_welovedatascience team

# Data 

Some data are already available on WeLoveDataScience Onedrive at following address.

[geostuff data at WeLoveDataScience](https://welovedatascience-my.sharepoint.com/:f:/p/eric_lecoutre/EnM7vbI6bt1KkKNXoX490uMBQW9QT4Yj3nWvnzuPFEV5_g?e=Agfn1H)

Currently, read only to prevent manipulation errors resulting in deletion.

Do not hesitate to contact Eric if you want to share additional data.

## Data listing

Following data are already there, all dealing with Wallonia.
Source: wallonia geoportal -- https://geoportail.wallonie.be/cartes-et-donnees/

* Aire covoiturage (vectorial - shapefile)
* Population density per 500m² (vectorial - shapefile)
* Companies; industries & services (vectorial - shapefile)
* Plan de Secteur (vectorial - shapefile)
* Projet Informatique de Cartographie Continue (PICC); 3 dimensional (vectorial - shapefile) (! huge, I did uncompress only Brabant Wallon, on which we can focus for prototype) (vectorial - shapefile)
* Secteurs statistiques (vectorial - shapefile) ; additional statbel information can be linked to that such as fiscal figures.
* Belgium OpenStreetMap data pbf format - to be used for instance per Osmosis
* Belgium OpenStreetMap data (vectorial - shapefile)

## Additional sources of data not yet there

* Schools in Wallonia, per type/degree [annuaire](http://www.enseignement.be/index.php?page=23836) -- to be geocoded
* SNCB+tec [trips planning](https://hello.irail.be/gtfs/) in GTSF format for OpenTripPlanner
* I may provide some properties transactional data (selling) for a subsection (for instance my municipality Villers-la-Ville), street level (no house number)


# Relevant software

* Rstudio+R: cf. [geospatial view](https://cran.r-project.org/web/views/Spatial.html) for packages listing. 
    + Free online book: [Geocomputation with R](https://geocompr.robinlovelace.net/)
* QGIS to visualize data https://www.qgis.org/
* nominatim+photon to geocode, cf [geocoder en masse avec R](https://rgeomatic.hypotheses.org/622)
* [OpenTripPlanner](https://www.opentripplanner.org/), multimodal trip planning (java).
