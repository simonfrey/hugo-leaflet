# Hugo Leaflet
OpenStreetMap Hugo Shortcodes 

## Installation

### [RECOMENDED] Load Scripts from CDN

1) Copy the _layouts_ folder over (containing the shortcuts)
2) Call the load shortcut in every post or globally in the theme
`{{< load-leaflet >}}`

###Load Scripts locally

1) Copy the _layouts_ folder over (containing the shortcuts)
2) Copy the _static_ folder (js & css)
3) Call the load shortcut in every post or globally in the theme
`{{< load-leaflet-local >}}`

## Usage

### Map only

*Shortcut*
`{{< leaflet-simple-marker mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]">}}`

*Parameters*
* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map

### Map with one marker


#### Marker _without_ Popup

*Shortcut*
`{{< leaflet-simple-marker mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]" markerLon="[MARKERLON]" markerLat="[MARKERLAT]">}}`

*Parameters*
* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map
* MARKERLON = longitude where to place the marker
* MARKERLAT = latitude where to place the marker

#### Marker _with_ Popup

*Shortcut*
`{{< leaflet-simple-marker mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]" markerLon="[MARKERLON]" markerLat="[MARKERLAT]" markerContent="[MARKERCONTENT]">}}`

*Parameters*
* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map
* MARKERLON = longitude where to place the marker
* MARKERLAT = latitude where to place the marker
* MARKERCONTENT = Content that should be displayed in marker popup (Can be HTML)

##License
GPL v2