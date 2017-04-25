# aframe-geojson-toolkit
A selection of different geoJSON components for A-Frame VR

## What's going to be here soon:
### geojson-globe component
An A-Frame component that allows you to to just pass a valid geoJSON to a geojson-globe component. The component will take of adding point or multipoint markers as aframe entities to a sphere with an equirectangular earh map as a material.
You can choose between an inside and an outside mode.

| Property | Settings | Notes |
| ---- | ---- |---- |
| geoData | path to a geoJson file or Object| NOTE: geoJSON Y, X not X, Y|
| markerColor | The color of the markers. |  |
| markerAsset | You can pass the id of an asset to use as a marker |  |
| markerLabel | default: false | if set to true, it uses label of entry |
| globeSrc | Material for the globe |  |
| globeRadius | radius of the globe |  |
| globeSide | inside / outside |  |

## globe component
interact with countries, choose countries to display
