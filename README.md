# hydrodataR
This package provides interfaces to hydrological data sources

Das Repository hydrodata-academy/hydrodataR stellt ein R-Paket bereit, das verschiedene Schnittstellen zu hydrologischen Datenquellen bietet. Es ermöglicht einfachen Zugriff auf aktuelle Rohdaten und geprüfte historische Daten. Das Paket kann direkt von GitHub installiert und über bereitgestellte Funktionen genutzt werden. Weitere Details und Beispiele sind in der Dokumentation zu finden. 

Installation
devtools::install_github("hydrodata-academy/hydrodataR")

library(hydrodataR)

# Datenquellen
Aktuell lassen sich Datenquellen wie folgt ermitteln
check_hub("type")

|type                |  content                   |
|--------------------|----------------------------|
|raw_nrw             |  Rohdaten der Pegelstände  |
|verified_runoff_nrw |  geprüfte Abflussdaten     |
|verified_level_nrw  |  geprüfte Wasserstandsdaten|




# Beispielaufruf einer Funktion
In der Datei example.R finden sich Beispiele für Datenanfragen


# Further Description
Unified access to environmental, ecological, and geospatial datasets. 
This R-package is a wrapper for several environmental data sets. At present it provides mainly access to data of NRW in Germany.

# GOAL
The aim is to provides a single, consistent API for retrieving, harmonizing, and working with environmental data from diverse online sources. It streamlines access to climate records, land-use indicators, biodiversity datasets, hydrological information, satellite products, and more—abstracting away the complexities of heterogeneous formats, endpoints, and metadata standards.
Designed for reproducible research, cross-domain analyses, and rapid data integration, the package supports caching, schema normalization, and scalable queries, making environmental data workflows simpler, faster, and more transparent.

Feel free to contribute


