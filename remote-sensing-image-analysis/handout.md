# Remote Sensing image analysis 

Handout von: [@jbalzer](https://github.com/jbalzer12), [@thalisgold](https://github.com/thalisgold)


## Auswahl aktuell verbreiteter Satellitenprogramme: 

* Landsat 8:
  * Start: 2013
  * Wiederholrate: 16 Tage
  * Auflösung: 15 m panchromatisch / VIS - SWIR 30 m
  * Liefert Aufnahmen im sichtbaren und infraroten Spektrum
  
[https://www.d-copernicus.de/](https://www.d-copernicus.de/daten/satelliten/satelliten-details/news/landsat-8/?tx_news_pi1%5Bcontroller%5D=News&tx_news_pi1%5Baction%5D=detail&cHash=c74ab3f39ecbc62a0a85cf3ee7b297fd) 

* Sentinel 1-3:
  * Teil des Copernicus-Programm der ESA
  * Sentinel 1:
    * Radar, 
    * Auflösung: 5 m
    * Start: 2014 (1A), 2016 (1B)
  * Sentinel 2:
    * passiv-optische Erdbeobachtung für Vegetation
    * Auflösung: 10 m
    * Start: 2015 (2A), 2017 (2B)
  * Sentinel 3:
    * Optisch/Thermisch für die Meere
    * Start: 2016 (3A), 2018 (3B)
  
[https://www.d-copernicus.de/](https://www.d-copernicus.de/daten/satelliten/daten-sentinels/)


## Datenformate

* Grafische Fernerkundungsdaten werden in der Regel als Rasterdaten gespeichert und enthalten “Bänder”, falls mehrere Farbkanäle existieren (vgl. [Nagesh Kumar](https://nptel.ac.in/courses/105/108/105108077/
))
* Mögliche Datentypen beim Download von Daten:


| Satellit | Mögliche Formate |
|:------------------ |:-------------------|
| Landsat             | .txt, .xml, .tif (GeoTIFF), (.jpeg)             |
| Sentinel 1 - Level 1            | .tif             |
| Sentinel 1 - Level 2            | .nc (NetCDF)             |
| Sentinel 2            | .jp2 (JPEG2000), .tif (GeoTIFF)             |
| Sentinel 3        | .nc (NetCDF)             |


* Downloadportale, an denen ich mich orientiert habe: 
  * [https://earthexplorer.usgs.gov](https://earthexplorer.usgs.gov) (Landsat, Sentinel 2)
  * [https://scihub.copernicus.eu/dhus/#/home](https://scihub.copernicus.eu/dhus/#/home) (Sentinel 1, Sentinel 2, Sentinel 3)

* Bsp. für einen cloudbasierten Downloaddienst: [https://browser.creodias.eu](https://browser.creodias.eu)
* Archiv des Landsat-Programms und erleichterte Auswahl der AOI über: [https://landsatlook.usgs.gov/explore](https://landsatlook.usgs.gov/explore)
