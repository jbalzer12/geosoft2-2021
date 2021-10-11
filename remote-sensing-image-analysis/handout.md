# Remote Sensing image analysis 

Handout von: [@jbalzer](https://github.com/jbalzer12), [@thalisgold](https://github.com/thalisgold)

## Was ist Fernerkundung?
* Kontaktfreies Erfassen von Informationen über eine Fläche
* Z.B. mit Sensoren, die an Satelliten, Flugzeugen oder Drohnen angebracht sind
* Sensor zeichnet elektromagnetische Strahlung auf, die an der Erdoberfläche und ihren Objekten reflektiert wird
* Das elektromagnetische Spektrum spielt in der Fernerkundung die zentrale Rolle
![EMS](img/EMS.jpg)
* Sie nutzt aus, dass jedes Material auf der Erde die elektromagnetische Strahlung anders reflektiert
* Daraus lassen sich letztlich Rückschlüsse auf Positionsinformationen von Objekten und Hinweise auf Eigenschaften von Oberflächen ziehen
* Wenn diese Rückschlüsse objektspezifisch und signifikant sind, können sie zur Objektklassifikation herangezogen werden!
* Wichtig: In der Fernerkundung sind auch Bereiche des EMS interessant, die das menschliche Auge nicht erfassen kann
* Bekanntes Beispiel: Vegetation reflektiert in nahem Infrarot besonders stark

## Vorteile Fernerkundung mit Satelliten

  * Großflächige Abdeckung
  * Häufige und sich wiederholende Abdeckung eines Interessenbereichs
  * Relativ niedrigere Kosten pro Einheitsgebiet der Abdeckung
  * Viele frei verfügbare Daten
  * Computergestützte Verarbeitung und Analyse

## Arten der Fernerkundung 

Man unterscheidet anhand des EMS drei große Bereiche:

* Optische Fernerkundung:
  * Meist passiv (empfangen Signale)
  * Umfasst den sichtbaren, den nahen und fernen Infrarotbereich
  *	Anfällig gegenüber Wolken/Aerosole
  *	Fernerkundungssysteme können abhängig von der Anzahl, der von ihnen verwendeten spektralen Kanäle in folgende Typen unterteilt werden:
    * Panchromatisch: Nur ein Kanal, der für Strahlung in einem breiten Wellenlängenbereich empfindlich ist.
    * Multispektral: 7-12 Kanäle. Jeder Kanal ist empfindlich gegenüber Strahlung innerhalb eines schmalen Wellenlängenbereichs. Das resultierende Bild ist ein mehrschichtiges Bild, das sowohl die Helligkeits- als auch die spektralen (Farb-) Informationen der beobachteten Objekte enthält
    * Hyperspektral: hundert oder mehr zusammenhängende Spektralkanäle
  * Bsp. für Satellit: Sentinel-2
    * 13 Kanäle/Bänder
    * Überfliegung alle 5 bis 7 Tage
    *	Auflösung 10/20/60m
* Vier Auflösungsdimensionen:
  * Zeitliche Auflösung (Variationen, z.B. Herbst/Frühling)
  * Räumliche Auflösung (Variationen, z.B. m/Pixel, d.h. Größenveränderung)
  * Radiometrische Auflösung (Anzahl der Informationen in bit, z.B. 8 bit, 16 bit etc.)
  *	Spektrale Auflösung (Wellenlängen, z.B. VIS und IR)
*	Radar Fernerkundung:
    *	Meist aktiv (senden Strahlung selbst aus und empfangen Signale als Energiepulse, die je nach Oberfläche unterschiedlich stark ausfallen)
    *	Aufnahmen unabhängig von Bewölkung und Tageszeit
*	Thermale Fernerkundung:
    *	Misst Temperatur der Erdoberfläche
    *	Bisher nur geringe räumliche Auflösung


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

