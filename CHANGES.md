# Changelog

## v1.1 - 2015-01-20

* Breaking changes
  * The `olFeatureId` has been removed from the picked Cesium counterpart.
    Use directly `olFeature` as illustrated in the synthetic vector examples.
  * The `olcs.OLCesium` constructor signature has changed. Use
    `new olcs.OLCesium({map: map, target: target});` instead of `new olcs.OLCesium(map, target);`
* Custom synchronizer function may be passed to the OLCesium constructor
* Core functions for implementing custom 2D-3D transitions à la Google Map
* Store the `ol.Feature` in the Cesium counterpart instead of an id.
  Use `primitive.olFeature` to read it after picking. See the synthetic vector examples.
* Allow 3D warmup while displaying the 2D map

## v1.0.0 - 2014-11-17
