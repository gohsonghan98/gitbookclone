# Map Component

The 'Map' component is used to display a location on a map within an interface.

## Properties

| Property                 | Value Sample      | Value Type | Description                                                       |
| ------------------------ | ----------------- | ---------- | ----------------------------------------------------------------- |
| Name                     | map1, map2        | string     | Specifies the name or identifier of the map component.            |
| Lat, Long                | 1.35531,103.86776 | string     | Specifies the latitude and longitude coordinates of the location. |
| Zoom                     | 10                | number     | Specifies the initial zoom level of the map.                      |
| Title                    | Orangekloud       | string     | Specifies the title or label for the map location.                |
| Show Zoom Control        | True, False       | boolean    | If set to true, shows the zoom control on the map.                |
| Show Map Type Control    | True, False       | boolean    | If set to true, shows the map type control on the map.            |
| Show Street View Control | True, False       | boolean    | If set to true, shows the street view control on the map.         |
| Show Full Screen Control | True, False       | boolean    | If set to true, shows the full screen control on the map.         |
| Show Route Markers       | True, False       | boolean    | If set to true, shows markers for the route on the map.           |

## Related Actions

* [mapSetCenter](../../../document/user-manual/ui-components/general/map/link\_to\_mapSetCenter/) - Sets the center of the map to the specified latitude and longitude coordinates.
* [mapSetZoom](../../../document/user-manual/ui-components/general/map/link\_to\_mapSetZoom/) - Sets the zoom level of the map to the specified value.
* [MapFitBounds](../../../document/user-manual/ui-components/general/map/link\_to\_MapFitBounds/) - Fits the map to contain the specified bounds.
* [mapAddMarker](../../../document/user-manual/ui-components/general/map/link\_to\_mapAddMarker/) - Adds a marker to the map at the specified latitude and longitude coordinates.
* [mapDeleteMarker](../../../document/user-manual/ui-components/general/map/link\_to\_mapDeleteMarker/) - Deletes the marker with the specified ID from the map.
* [mapClearMarker](../../../document/user-manual/ui-components/general/map/link\_to\_mapClearMarker/) - Removes all markers from the map.
* [mapRoute](../../../document/user-manual/ui-components/general/map/link\_to\_mapRoute/) - Calculates and displays a route on the map from the starting coordinates to the ending coordinates.
* [mapSetClickListener](../../../document/user-manual/ui-components/general/map/link\_to\_mapSetClickListener/) - Sets a callback function to be executed when the user clicks on the map.
* [mapGetZoom](../../../document/user-manual/ui-components/general/map/link\_to\_mapGetZoom/) - Retrieves the current zoom level of the map.
* [intentMaps](../../../document/user-manual/ui-components/general/map/link\_to\_intentMaps/) - Opens the default maps application with a marker at the specified latitude and longitude coordinates and the given title.

## Example Uses

N/A
