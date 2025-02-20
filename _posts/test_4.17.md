---
title: "This is a test!!!"
date: 2019-04-13
published: true
tags: [dataviz, altair, vega-lite, observable, holoviews]
excerpt: "Embedding interactive charts on static pages using Jekyll."
altair-loader:
  altair-chart: "charts/measlesAltair.json"
observable-loader:
  url: https://api.observablehq.com/@nickhand/embedding-altair-plots-in-observable.js
  names:
    vega-chart: "heatmap"
hv-loader:
  holoviews-chart: "charts/measlesHoloviews.html"
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) [Vega-Lite](https://vega.github.io/vega-lite/) via [Observable](https://observablehq.com/), and
[Holoviews](http://holoviews.org/index.html).

## Altair Example

Below is a chart of the incidence of measles since 1928 for the 50 US states.

<div id="altair-chart"></div>
