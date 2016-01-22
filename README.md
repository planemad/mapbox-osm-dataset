# mapbox-osm-dataset
**A node module to manage an existing Mapbox dataset using OpenStreetMap data.**

## Usage
Update an existing Mapbox dataset using the results of an Overpass query
`mapbox-osm-dataset 'mapbox_username.mapid' 'overpass_query' `

eg. `mapbox-osm-dataset 'planemad.1m2kxxim' '[out:json][timeout:25];(node["highway"="bus_stop"](12.946554043930224,77.56158828735352,12.983816808126269,77.62420177459717););out body;>;out skel qt;'`
