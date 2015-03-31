# Maps

Repository of map data used by Downtown Grand Rapids Inc.'s website, [Pearl](http://downtowngr.org).

## Boards

`dda_boudary.geojson` - Downtown Development Authority service boundary.
`dda_tifa.geojson` - Downtown Development Authority TIF collection boundary.
`did_service.geojson` - Downtown Improvement District service boundary.
`monroenorth_tifa.geojson` - Monroe North TIFA collection boundary.

## Transportation

`bike_parking.geojson` - Bike Parking within Downtown collected through OpenStreetMap.
`lots_and_entrances.geojson` - All public and private parking lots and ramps within Downtown, including entrance points.
`parking_meters.geojson` - Parking meter blocks and prices. Adapted from [Parking Services data](http://grcity.us/enterprise-services/Parking-Services/Pages/Parking-Meter-Map.aspx).
`transit_stops.geojson` - All bus stops, their numbers, names, and routes within Downtown. Adapted from [The Rapid's GTFS feed](http://data.grcity.us/dataset/gtfs).

Includes shapefiles used to produce `lots_and_entrances.geojson`. Data collected by DGRI.

### Bounding Box

Bounding box for Downtown points should be within a polygon from the intersection of 6th St NW and Seward Ave NW on the northwestern edge (`42.97696419731116, -85.68291485309601`) to the intersection of College Ave SE and Logan St SE on the southeastern edge (`42.95390977598836, -85.65665602684021`).

## License

These maps are made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/

For a clear, human readable explanation of this License, read this: http://opendatacommons.org/licenses/odbl/summary/