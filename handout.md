# Datenwürfel für Fernerkundungsdaten, Klimamodelle und Wetterdaten
@neli98

## Datenwürfel allgemein
* auch bekannt als OLAP-Würfel (OLAP = Online Analytical Processing)
* relevant im Bereich des Data-Warehousing
* nützlich zur einfachen Strukturierung von Daten
* beliebig viele Dimensionen
* Speicherung der Daten in einzelnen Elementen des Würfels
  * leicht vorzustellen bei 3D-Würfel
* unterschiedliche Dimensionen ermöglichen dynamische Betrachtungsweise der Daten aus verschiedenen Perspektiven
* verschiedene Grundoperationen, wie z.B.:
  * Slice-Operation (Ausschneiden einer Datenscheibe)
  * Dice-Operation (Erzeugen eines kleineren Würfels aus Ursprungswürfel)
  * Drill-Down-Operation (Hineinzoomen und Auslesen detaillierterer Daten)

## Datenwürfel im geographischen Kontext

### Anwendungsfälle
* hilfreich beim Umgang mit großen GIS-Datenmengen, speziell Earth Observation(EO)-Daten
* Analyse von z.B.:
  * Abholzung/Rodung von Wäldern
  * illegalem Rohstoffabbau
  * Dürreregionen
  * Bedeckung des Bodens durch Schnee
  * Wetterentwicklungen

Quelle: https://www.ecmwf.int/sites/default/files/elibrary/2018/18723-open-data-cube-odc-tool-increase-value-and-impact-global-earth-observation-satellite-data.pdf

### Beispiele
* Open Data Cube (https://www.opendatacube.org)
  * internationale Open-Source Initiative
  * Bereitstellung und Analyse von EO-Daten zur Unterstützung der Erreichung beispielsweise der SDG's
* Next Generation Network Enabled Weather Project (https://en.wikipedia.org/wiki/Next_Generation_Network_Enabled_Weather)
  * Initiative der USA
  * 4D-Wetterdaten-Würfel
  * Analyse von Wetterdaten zur besseren Wettervorhersage und Optimierung des Flugverkehrs
* Earth Server (http://www.gis-news.de/earthserver-1-petabyte-analysis-ready-datacubes/)
  * Initiative unterstützt durch die EU
  * Bereitstellung von 3D-Satellitendaten und 4D-Wetterdaten

### Vorteile
* Bereitstellung eines zentralen Datenpools
* flexibler Zugriff auf ausgewählte Datenausschnitte möglich
* flexible Anwendbarkeit, z.B. über Cloud-Services oder lokal
* Ermöglichung der (einfachen) Analyse großer Datenmengen

### Nachteile
* Bildung von Datenwürfeln aufgrund großer Datenmengen oftmals zeitaufwendig
* Notwendigkeit der Vorstrukturierung der Daten
* Performance abhängig von Datenmengen



Fragen:
soll ich auch auf relationale und multidimensionale OLAPS und deren Unterschiede eingehen?
Wie sehr soll ich auf Datenwürfel im Allgemeinen eingehen (beziehen sich Vor- und Nachteile zum Beispiel darauf oder eher auf die Beispiele?)
