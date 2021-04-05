# OpenStreetMap Danmarks cykelstinetværk & trapper
Dansk guide til import af Danmarks cykelnetværk og trapper med osm2pgsql værktøjet ind i PostgreSQL/PostGIS. Data kommer fra OpenStreetMap.
I cyclenetwork.style filen findes trin for trin vejledningen. Filen er en tekst fil, så du kan åbne den med din sædvanlige teksteditor.
Såfremt du laver ændringer i style file, så husk at gemme med .style i filnavnet ellers vil  osm2pgsql ikke kunne læse den.

Data: OpenStreetMap Danmark kommer fra Geofabrik download arkiv. 

Software der bruges i denne guide er osmfilter, osmconvert64, PostgreSQL med PostGIS, osm2pgsql.
Guide tager udgangspunkt i at man allerede har en PostgreSQL med PostGIS databaseserver kørende. Det kan være lokal version eller en på et netværk.

