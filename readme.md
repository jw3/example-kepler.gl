Kepler.gl + MF-JSON
===

Uses MF-JSON reshaped for a Kepler.gl Trip Layer

The Moving Features JSON (MF-JSON) was built with MobilityDB's Mobility Engine, Open Source (MEOS) and reshaped for display in a Kepler.gl Trip Layer. 
The original AIS dataset was filtered to include vessels with tracks longer than 250 posits and assembled from a single data of AIS data (01-01-2020).

![screenshot](doc/img.png)

### Live demo

Deployed to GitHub Pages

1. [Large json](https://jw3.github.io/example-kepler.gl?f=kgl-3731-500.json) ~3700 vessels
2. [Medium json](https://jw3.github.io/example-kepler.gl?f=kgl-1000-500.json) ~1000 vessels 

The default pages url, without query param, loads the 1000 vessel dataset.

### reference

- https://mobilitydb.com/
- https://www.libmeos.com/
- https://docs.ogc.org/is/19-045r3/19-045r3.html
- https://docs.kepler.gl/docs/user-guides/c-types-of-layers/k-trip
