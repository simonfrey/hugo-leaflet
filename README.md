# Hugo Leaflet

Shortcodes for inserting a OSM (Open Street Maps) Map into your posts by using leaflet.

_You can use as much Maps in a single post as you like! (You only have to load the script once)_


---

Help me to grow this project:

[![Donate Button](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/l1am0)

---

## Installation/Loading necessary scripts

[Download the project as ZIP](https://github.com/L1am0/hugo-leaflet/archive/master.zip)

### [RECOMENDED] Load Scripts from CDN

1) Copy the _layouts_ folder over (containing the shortcuts)
2) Call the load shortcut in every post or globally in the theme
`{{< load-leaflet >}}`

### Load Scripts locally
**Only with "Map only" working**

1) Copy the _layouts_ folder over (containing the shortcuts)
2) Copy the _static_ folder (js & css)
3) Call the load shortcut in every post or globally in the theme
`{{< load-leaflet-local >}}`

## Usage

### Map only

**Shortcut**

`{{< leaflet-simple mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]" zoom="[ZOOM]">}}`

**Parameters**

* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map
* ZOOM = the zoom level. This attribute is optional, default zoom level is 13. If set, it must be parsable as int.

### Map with one marker


#### Marker _without_ Popup

**Shortcut**

`{{< leaflet-simple mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]" markerLon="[MARKERLON]" markerLat="[MARKERLAT]">}}`

**Parameters**

* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map
* MARKERLON = longitude where to place the marker
* MARKERLAT = latitude where to place the marker

#### Marker _with_ Popup

**Shortcut**

`{{< leaflet-simple mapHeight="[MAPHEIGHT]" mapWidth="[MAPWIDTH]" mapLon="[MAPLON]" mapLat="[MAPLAT]" markerLon="[MARKERLON]" markerLat="[MARKERLAT]" markerContent="[MARKERCONTENT]">}}`

**Parameters**

* MAPHEIGHT = px | %
* MAPWIDTH = px (must be pixels! Otherwise the map will not be shown)
* MAPLON = longitude where to center the map
* MAPLAT = latitude where to center the map
* MARKERLON = longitude where to place the marker
* MARKERLAT = latitude where to place the marker
* MARKERCONTENT = Content that should be displayed in marker popup (Can be HTML)

## Donate

**If you like my work please support me! With your support I can go on improving the current shortcuts and add new ones**

**[BUY ME A MATE TEA](http://l1am0.eu/donate.php)**

## License
GPL v2

---
Open Street Map, Hugo, HugoCMS, Leaflet, Maps, Hugo Maps Plugin, Shortcut, OSM, Osmand
