# Mapbox Free Draw Mode

This is a custom mode for [@mapbox/mapbox-gl-draw]() that adds draw functionality to the draw polygon mode.

## Demo
https://bemky.github.io/mapbox-gl-draw-free-mode/

## Usage

To install:

`npm i @bemky/mapbox-gl-draw-free-mode`

To add to MapboxDraw:

```js
require('@mapbox/mapbox-gl-draw-free-mode');

// Then build map with draw like usual
var map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/mapbox/streets-v8',
  center: [40, -74.50],
  zoom: 9
});
var Draw = new MapboxDraw();
map.addControl(Draw)

```

## Build
`grunt build`

## Serve
`grunt serve`

## Deploy Demo
`grunt deploy`
