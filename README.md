<img alt="nivo" src="https://raw.githubusercontent.com/plouc/nivo/master/nivo.png" width="216" height="68"/>

[![License][license-image]][license-url]
[![Travis CI][travis-image]][travis-url]
[![NPM version][npm-image]][npm-url]
[![nivo channel on discord](https://img.shields.io/badge/discord-nivo-61dafb.svg?style=flat-square)](https://discord.gg/n7Ft74f)
[![Dependencies][gemnasium-image]][gemnasium-url]
[![styled with prettier][prettier-image]][prettier-url]

**nivo** provides supercharged React components to easily build dataviz apps,
it's built on top of d3.

Several libraries already exist for React d3 integration,
but just a few provide server side rendering ability and fully declarative charts.

## Installation

In order to use nivo, you just have to pick the scoped `@nivo` packages according to the charts you wish to use.

```
yarn add @nivo/bar @nivo/sankey ...
```

## Features

* Highly customizable
* Motion/transitions, powered by [react-motion](https://github.com/chenglou/react-motion)
* [Component playground](http://nivo.rocks)
* [Exhaustive documentation](http://nivo.rocks)
* Isomorphic rendering
* [SVG charts](http://nivo.rocks/#/components?filter=svg)
* [HTML charts](http://nivo.rocks/#/components?filter=html)
* [Canvas charts](http://nivo.rocks/#/components?filter=canvas)
* [server side rendering API](https://github.com/plouc/nivo-api)
* [SVG patterns](http://nivo.rocks/#/guides/patterns)
* [Gradients](http://nivo.rocks/#/guides/gradients)
* [responsive charts](http://nivo.rocks/#/components?q=responsive)

## Discussion

Join the [nivo discord community](https://discord.gg/n7Ft74f).

## Components

* Bar `@nivo/bar`
  * [`<Bar/>`](http://nivo.rocks/#/bar)
  * [`<ResponsiveBar/>`](http://nivo.rocks/#/bar)
  * [`<BarCanvas/>`](http://nivo.rocks/#/bar/canvas)
  * [`<ResponsiveBarCanvas/>`](http://nivo.rocks/#/bar/canvas)
* Bubble `@nivo/circle-packing`
  * [`<Bubble/>`](http://nivo.rocks/#/bubble)
  * [`<ResponsiveBubble/>`](http://nivo.rocks/#/bubble)
  * [`<BubbleHtml/>`](http://nivo.rocks/#/bubble/html)
  * [`<ResponsiveBubbleHtml/>`](http://nivo.rocks/#/bubble/html)
  * [`<BubbleCanvas/>`](http://nivo.rocks/#/bubble/canvas)
  * [`<ResponsiveBubbleCanvas/>`](http://nivo.rocks/#/bubble/canvas)
* Calendar `@nivo/calendar`
  * [`<Calendar/>`](http://nivo.rocks/#/calendar)
  * [`<ResponsiveCalendar/>`](http://nivo.rocks/#/calendar)
* Chord `@nivo/chord`
  * [`<Chord/>`](http://nivo.rocks/#/chord)
  * [`<ResponsiveChord/>`](http://nivo.rocks/#/chord)
  * [`<ChordCanvas/>`](http://nivo.rocks/#/chord/canvas)
  * [`<ResponsiveChordCanvas/>`](http://nivo.rocks/#/chord/canvas)
* HeatMap `@nivo/heatmap`
  * [`<HeatMap/>`](http://nivo.rocks/#/heatmap)
  * [`<ResponsiveHeatMap/>`](http://nivo.rocks/#/heatmap)
  * [`<HeatMapCanvas/>`](http://nivo.rocks/#/heatmap/canvas)
  * [`<ResponsiveHeatMapCanvas/>`](http://nivo.rocks/#/heatmap/canvas)
* Line `@nivo/line`
  * [`<Line/>`](http://nivo.rocks/#/line)
  * [`<ResponsiveLine/>`](http://nivo.rocks/#/line)
* Pie `@nivo/pie`
  * [`<Pie/>`](http://nivo.rocks/#/pie)
  * [`<ResponsivePie/>`](http://nivo.rocks/#/pie)
* Radar `@nivo/radar`
  * [`<Radar/>`](http://nivo.rocks/#/radar)
  * [`<ResponsiveRadar/>`](http://nivo.rocks/#/radar)
* Sankey `@nivo/sankey`
  * [`<Sankey/>`](http://nivo.rocks/#/sankey)
  * [`<ResponsiveSankey/>`](http://nivo.rocks/#/sankey)
* Stream `@nivo/stream`
  * [`<Stream/>`](http://nivo.rocks/#/stream)
  * [`<ResponsiveStream/>`](http://nivo.rocks/#/stream)
* Sunburst `@nivo/sunburst`
  * [`<Sunburst/>`](http://nivo.rocks/#/sunburst)
  * [`<ResponsiveSunburst/>`](http://nivo.rocks/#/sunburst)
* TreeMap `@nivo/treemap`
  * [`<TreeMap/>`](http://nivo.rocks/#/treemap)
  * [`<ResponsiveTreeMap/>`](http://nivo.rocks/#/treemap)
  * [`<TreeMapHTML/>`](http://nivo.rocks/#/treemap/html)
  * [`<ResponsiveTreeMapHTML/>`](http://nivo.rocks/#/treemap/html)
  * [`<TreeMapCanvas/>`](http://nivo.rocks/#/treemap/canvas)
  * [`<ResponsiveTreeMapCanvas/>`](http://nivo.rocks/#/treemap/canvas)
* Voronoi `@nivo/voronoi`
  * [`<Voronoi/>`](http://nivo.rocks/#/voronoi)
  * [`<ResponsiveVoronoi/>`](http://nivo.rocks/#/voronoi)

## [HTTP API](https://github.com/plouc/nivo-api)

* [`<Bar/>`](https://nivo-api.herokuapp.com/samples/bar.svg)
* [`<Bubble/>`](https://nivo-api.herokuapp.com/samples/bubble.svg)
* [`<Chord/>`](https://nivo-api.herokuapp.com/samples/chord.svg)
* [`<HeatMap/>`](https://nivo-api.herokuapp.com/samples/heatmap.svg)
* [`<Line/>`](https://nivo-api.herokuapp.com/samples/line.svg)
* [`<Pie/>`](https://nivo-api.herokuapp.com/samples/pie.svg)
* [`<Radar/>`](https://nivo-api.herokuapp.com/samples/radar.svg)
* [`<Sankey/>`](https://nivo-api.herokuapp.com/samples/sankey.svg)
* [`<Sunburst/>`](https://nivo-api.herokuapp.com/samples/sunburst.svg)
* [`<TreeMap/>`](https://nivo-api.herokuapp.com/samples/treemap.svg)

## Guides

* [colors](http://nivo.rocks/#/guides/colors)
* [gradients](http://nivo.rocks/#/guides/gradients)
* [patterns](http://nivo.rocks/#/guides/patterns)

## Repositories

* [nivo](https://github.com/plouc/nivo) - the nivo library
* [nivo-api](https://github.com/plouc/nivo-api) - the nivo http api
* [nivo-api-docker](https://github.com/plouc/nivo-api-docker) - a Docker image for the nivo http api
* [nivo-generators](https://github.com/plouc/nivo-generators) - the data generators used for nivo-website and http API samples

## Credits

* [d3](https://d3js.org/)
* [react](https://facebook.github.io/react/)
* [react-motion](https://github.com/chenglou/react-motion)
* …

[license-image]: https://img.shields.io/github/license/plouc/nivo.svg?style=flat-square
[license-url]: https://github.com/plouc/nivo/blob/master/LICENSE.md
[npm-image]: https://img.shields.io/npm/v/@nivo/core.svg?style=flat-square
[npm-url]: https://www.npmjs.com/~nivo
[travis-image]: https://img.shields.io/travis/plouc/nivo.svg?style=flat-square
[travis-url]: https://travis-ci.org/plouc/nivo
[prettier-image]: https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=flat-square
[prettier-url]: https://github.com/prettier/prettier
[gemnasium-image]: https://img.shields.io/gemnasium/plouc/nivo.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/plouc/nivo
