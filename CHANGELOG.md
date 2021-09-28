# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.2.10](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.9...v6.2.10) (2021-09-28)

**Note:** Version bump only for package @nativescript-community/ui-mapbox





## [6.2.9](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.8...v6.2.9) (2021-05-07)


### Bug Fixes

* correctly implement padding ([79f98a0](https://github.com/nativescript-community/ui-mapbox/commit/79f98a0f0d7389431eb3b2226b2ef5c08a89cdef))





## [6.2.8](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.7...v6.2.8) (2021-03-30)


### Features

* basic cluster support ([47f0f0d](https://github.com/nativescript-community/ui-mapbox/commit/47f0f0df02a1888092e755eb94d448cc8524f802))





## [6.2.7](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.6...v6.2.7) (2021-02-25)


### Bug Fixes

* **ios:** missing camera events ([bc7af99](https://github.com/nativescript-community/ui-mapbox/commit/bc7af99a9579967d606d5d618de99203970de4d5))





## [6.2.6](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.5...v6.2.6) (2021-02-20)


### Features

* animateCamera supports bounds and zoomLevel on both platforms ([11f883a](https://github.com/nativescript-community/ui-mapbox/commit/11f883adc2d24f86e533cedc62503fb15526cb26))





## [6.2.5](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.4...v6.2.5) (2021-02-18)


### Bug Fixes

* **android:** project result in dpi ([6112f37](https://github.com/nativescript-community/ui-mapbox/commit/6112f37f812c706f56fb6b27e5fd4b5e8c0db412))





## [6.2.4](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.3...v6.2.4) (2021-02-18)


### Features

* mapClick event available the N way ([1965f4b](https://github.com/nativescript-community/ui-mapbox/commit/1965f4bd884cf901e897329b0a69f8488f826542))





## [6.2.3](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.2...v6.2.3) (2021-02-09)


### Bug Fixes

* some style property conversion fixes ([26cce82](https://github.com/nativescript-community/ui-mapbox/commit/26cce824ef892de2d48479e14048148d867e5bd3))


### Features

* project method to go from latlng to screen coords ([3d6131a](https://github.com/nativescript-community/ui-mapbox/commit/3d6131a8765b47fae32201f4c91254cbbb7d2353))
* setLogLevel ([659dace](https://github.com/nativescript-community/ui-mapbox/commit/659daceb3e16c09117c6d69905e90725c8a12d85))
* source-layer support for layers ([6b56ea8](https://github.com/nativescript-community/ui-mapbox/commit/6b56ea8a6cdd0e4fb6c72900690fea74dcdfadec))





## [6.2.2](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.1...v6.2.2) (2021-02-07)


### Bug Fixes

* **ios:** icon-allow-overlap fix ([5c3f70d](https://github.com/nativescript-community/ui-mapbox/commit/5c3f70d6307e6a829802ed1bf45dc3e3faa8bcbc))
* **ios:** prevent crash when ‘click’ mapEvent not set ([8d5a0e2](https://github.com/nativescript-community/ui-mapbox/commit/8d5a0e230a9761b1398b4fb1d62c0d11c0d9d4e6))





## [6.2.1](https://github.com/nativescript-community/ui-mapbox/compare/v6.2.0...v6.2.1) (2021-02-07)


### Bug Fixes

* **android:** cache marker images => crazy faster addMarkers ([f2f4a22](https://github.com/nativescript-community/ui-mapbox/commit/f2f4a22cc680c170a29e0169affeb0c5d4e4dd5f))
* **android:** ensure map exists on destroy ([1b36396](https://github.com/nativescript-community/ui-mapbox/commit/1b36396ec79a84d852232db57a54245efbee3425))


### Features

* added more source options ([a75fc27](https://github.com/nativescript-community/ui-mapbox/commit/a75fc27921c73386f463168db854ecd10f71e22f))
* almost all style prpoerties are now supported. You can also put any expression you want! ([d3e5e42](https://github.com/nativescript-community/ui-mapbox/commit/d3e5e42b62c830cb255a02e26165f3a85a26cebc))
* belowLayerId support for addLayer ([4551401](https://github.com/nativescript-community/ui-mapbox/commit/4551401c6181a8749f542443348c38aa7ab938fc))
* layer minzoom maxzoom support ([880761f](https://github.com/nativescript-community/ui-mapbox/commit/880761f3d21df91677f09af4622965f730a27f37))
* updateSource (for now only to update geojson data) ([e593480](https://github.com/nativescript-community/ui-mapbox/commit/e593480f24ec819b0ace3adc6e8cb51b58a6c081))
* **ios:** setOnCameraIdleListener && setOnCameraMoveListener ([fa640cd](https://github.com/nativescript-community/ui-mapbox/commit/fa640cdd44bd5d7efeac89d6c56f05ad32d5cf22))





# [6.2.0](https://github.com/nativescript-community/ui-mapbox/compare/v6.1.0...v6.2.0) (2020-12-30)


### Features

* (android) color support for LocationComponent ([c81b4d1](https://github.com/nativescript-community/ui-mapbox/commit/c81b4d14e418b011fa7235853645c64f4295cad8))
* getImage and removeImage ([8aa323b](https://github.com/nativescript-community/ui-mapbox/commit/8aa323b211463879e5f9a5e58a3db7dcb1dbb71c))
* method querySourceFeatures ([#16](https://github.com/nativescript-community/ui-mapbox/issues/16)) ([1812e00](https://github.com/nativescript-community/ui-mapbox/commit/1812e00429818360a7b041cd3fb168677a17a751))





# [6.1.0](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.7...v6.1.0) (2020-12-23)


### Bug Fixes

* (android) actually removing source from the map in "removeSource" ([b8b279f](https://github.com/nativescript-community/ui-mapbox/commit/b8b279f96ec4fd1b66ced4accb9149a88978d9d0))
* (android) circle-radius of type number used wrong property (caused crash) ([3a944b3](https://github.com/nativescript-community/ui-mapbox/commit/3a944b3cadeac81ffa3f97332503b52f9a4dab14))
* addLinePoint and deprecated for next version ([5865dae](https://github.com/nativescript-community/ui-mapbox/commit/5865dae3cd310c1e0db0772675100038a3ef43b6))
* addSource on v8-ios-runtime + support for all geojson types including FeatureCollection ([38728b8](https://github.com/nativescript-community/ui-mapbox/commit/38728b8d2629452f4c86a15182396f4b823f81b8))
* addSource/addLayer on android ([a6dd1c2](https://github.com/nativescript-community/ui-mapbox/commit/a6dd1c289dfc45c24cd57fd4c27881bb552a9b11))
* replace tilde in markers iconPath (so ~ would work on both android and ios) ([4b72713](https://github.com/nativescript-community/ui-mapbox/commit/4b72713f98dca34d167cfe65c63789909219700d))
* replaced broken addMarker demo icons ([91979ff](https://github.com/nativescript-community/ui-mapbox/commit/91979ff4b77e18ee27a768345f54f1e995a9a2a5))


### Features

* (android) support for all geojson types in addSource ([26ce92a](https://github.com/nativescript-community/ui-mapbox/commit/26ce92a6898283b9bb7cf60d2f3d395c6344c022))
* added addImage + SymbolLayer support ([d104637](https://github.com/nativescript-community/ui-mapbox/commit/d104637516cced10515ad0ce6b93c2f06016572d))
* added visibility layout property support to all layer types. added circle-pitch and circle-translate property support ([6510e9d](https://github.com/nativescript-community/ui-mapbox/commit/6510e9d30b44ec48bcf2e34ab8094dc2789ee44e))
* click event for any layer types ([#9](https://github.com/nativescript-community/ui-mapbox/issues/9)) ([908dbd4](https://github.com/nativescript-community/ui-mapbox/commit/908dbd4e6627d655d200717428d94772e8bc5e84))
* more paint and layout properties for LineLayer supported ([7a9bd38](https://github.com/nativescript-community/ui-mapbox/commit/7a9bd3846300f6155f5e87d6d54ad76977b5fbf9))
* raster source & layer support ([#11](https://github.com/nativescript-community/ui-mapbox/issues/11)) ([c485595](https://github.com/nativescript-community/ui-mapbox/commit/c485595a52cb73b5d5f17ece46dc353d10dad130))
* setFilter/getFilter for layers ([#7](https://github.com/nativescript-community/ui-mapbox/issues/7)) ([e893dd5](https://github.com/nativescript-community/ui-mapbox/commit/e893dd5b4f461b6a432b92d7bb2dc63ffb60c973))





## [6.0.7](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.6...v6.0.7) (2020-11-25)


### Bug Fixes

* android lifecycle fix ([2c3731a](https://github.com/nativescript-community/ui-mapbox/commit/2c3731a9f454b3d861fd8b4ea7a58f11fef4037a))
* correctly handle lifecycle ([e4e3fd9](https://github.com/nativescript-community/ui-mapbox/commit/e4e3fd9fa9c45c6c0c6174d305443b09078c7d19))





## [6.0.6](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.5...v6.0.6) (2020-11-23)

**Note:** Version bump only for package @nativescript-community/ui-mapbox





## [6.0.5](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.4...v6.0.5) (2020-11-22)


### Bug Fixes

* typo ([e841223](https://github.com/nativescript-community/ui-mapbox/commit/e841223b6b89a579ece1886ad250f787dd7395d0))





## [6.0.4](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.3...v6.0.4) (2020-11-19)


### Bug Fixes

* android bug where map would remain black ([19a0b67](https://github.com/nativescript-community/ui-mapbox/commit/19a0b6788c6574a4376e2a74c7e6b2e610606cd6))
* npm script paths corrected, removed obsolete test scripts. reset scripts use ns clean. fixed readme ([94ebe11](https://github.com/nativescript-community/ui-mapbox/commit/94ebe11f781adf3dd9a9b6f4e6ef7c16cada91ac))


### Features

* getLayer + getLayers ([0b3f882](https://github.com/nativescript-community/ui-mapbox/commit/0b3f8826308b4e8a5bf5665fccd481cdf0900ac0))





## [6.0.3](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.2...v6.0.3) (2020-11-13)


### Bug Fixes

* android disabling telemetry too soon ([1f0c6e5](https://github.com/nativescript-community/ui-mapbox/commit/1f0c6e59cc99ec6f557eaec67c5910bff4d633da))





## [6.0.2](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.1...v6.0.2) (2020-11-13)


### Bug Fixes

* force pod version in demo ([88ad6a8](https://github.com/nativescript-community/ui-mapbox/commit/88ad6a8842be1310dc2b4f6d536cd28d0b7ee889))
* some fixes ([b452da4](https://github.com/nativescript-community/ui-mapbox/commit/b452da426815e02eeb7d4be1dc13f8765eba97cf))
* telemetry false by default. GDRP compliant ([a4a5f2d](https://github.com/nativescript-community/ui-mapbox/commit/a4a5f2d10ef8f4ec41aa17fa09a0267725383921))





## [6.0.1](https://github.com/nativescript-community/ui-mapbox/compare/v6.0.0...v6.0.1) (2020-11-12)


### Bug Fixes

* android fix for anroid 11 ([97e1ad8](https://github.com/nativescript-community/ui-mapbox/commit/97e1ad86cb06c48e74712fbc8bdfcabdb854ab94))
* android fixes ([4cb6407](https://github.com/nativescript-community/ui-mapbox/commit/4cb640773ffce644ac6b2f6680197fef29821652))





# 6.0.0 (2020-11-12)


### Bug Fixes

* avoid "property of null" error ([45533b7](https://github.com/nativescript-community/ui-mapbox/commit/45533b734d0f0c70f25cef8c2a70cea18458014d))
* ios upgraded sdk ([41785b9](https://github.com/nativescript-community/ui-mapbox/commit/41785b91f4bd6ba3a5b3aa6547c0e4c156a3363e))



# 4.4.0 (2018-10-15)



## 4.3.1 (2018-10-11)



# 4.3.0 (2018-09-25)



# 4.2.0 (2018-08-14)



## 4.1.2 (2018-08-13)



## 4.1.1 (2018-07-03)



# 4.1.0 (2018-07-02)



# 4.0.0 (2018-05-07)



# 3.3.0 (2018-01-20)



## 3.1.3 (2017-11-02)



## 3.1.2 (2017-09-12)



# 3.1.0 (2017-08-17)



## 3.0.3 (2017-08-08)



## 3.0.2 (2017-08-05)



## 3.0.1 (2017-07-12)



# 3.0.0 (2017-04-25)



## 2.6.1 (2017-04-01)



# 2.6.0 (2017-03-22)



## 2.5.3 (2017-03-16)



## 2.5.2 (2017-03-04)



## 2.5.1 (2017-01-29)



# 2.5.0 (2017-01-29)



# 2.4.0 (2017-01-19)



## 2.3.2 (2017-01-09)



## 2.3.1 (2016-12-05)



# 2.3.0 (2016-11-16)



## 2.2.4 (2016-11-16)



## 2.2.3 (2016-11-11)



## 2.2.2 (2016-11-03)



## 2.2.1 (2016-10-26)



# 2.2.0 (2016-10-26)



## 2.1.1 (2016-10-25)



# 2.1.0 (2016-10-15)



# 2.0.0 (2016-10-12)



# 1.5.0 (2016-09-23)



# 1.4.0 (2016-08-24)



# 1.3.0 (2016-07-18)



## 1.2.1 (2016-07-09)



## 1.1.2 (2016-03-16)



## 1.1.1 (2016-02-04)



# 1.1.0 (2016-02-04)



## 1.0.5 (2015-12-22)



## 1.0.4 (2015-11-03)



## 1.0.2 (2015-10-28)



## 1.0.1 (2015-10-08)



# 1.0.0 (2015-10-03)





# Change Log

[Android SDK](https://github.com/mapbox/mapbox-gl-native/blob/master/platform/android/CHANGELOG.md)

[iOS SDK](https://github.com/mapbox/mapbox-gl-native/blob/master/platform/ios/CHANGELOG.md)

## 5.0.0-alpha.2 

**Implemented enchancements:**

- bumped Mapbox Android SDK to 9.0.0
- fixed merge with upstream

**Fixed Bugs**

- iOS demo works once again.

## 5.0.0-alpha.1 
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/5.0.0-alpha.1...4.4.0)

**Implemented enchancements:**

- bumped Mapbox iOS SDK version to 5.1.1 and Android SDK's to 8.4.0
- added methods: addLayer()/removeLayer()/addLinePoint()/addSource()/removeSource()
- support for rendering GeoJSON lines and circles
- support for adding click handlers to lines and circles.

**Fixed Bugs**

- this hopefully fixes the Android crash bug.

## [4.4.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.4.0) (2018-10-15)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.3.1...4.4.0)

**Implemented enhancements:**

- Bump Mapbox iOS and Android SDK [\#269](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/269)

**Fixed bugs:**

- draw the user trip [\#268](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/268)


## [4.3.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.3.1) (2018-10-11)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.3.0...4.3.1)

**Implemented enhancements:**

- LongPress functionality for android and ios [\#266](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/266)


## [4.3.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.3.0) (2018-09-25)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.2.0...4.3.0)

**Implemented enhancements:**

- Allow Mapbox to load local json map style definition [\#261](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/261)


## [4.2.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.2.0) (2018-08-14)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.1.2...4.2.0)

**Implemented enhancements:**

- Feature Request: Move Map Markers [\#226](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/226)
- Update Mapbox iOS SDK to 4.2.0 [\#248](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/248)

## [4.1.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.1.2) (2018-08-13)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.1.1...4.1.2)

**Implemented enhancements:**

- OnPermissionDenied [\#247](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/247)

## [4.1.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.1.1) (2018-07-03)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.1.0...4.1.1)

**Implemented enhancements:**

- Add a method to remove polygons [\#237](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/237)

## [4.1.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.1.0) (2018-07-02)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/4.0.0...4.1.0)

**Fixed bugs:**

- RemoveMarkers doesnt work [\#229](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/229)
- removeMarkers broken on Android. [\#231](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/231)

**Implemented enhancements:**

- User Tracking Mode [\#144](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/144)
- Build error on Android, related to source level 1.8 [\#234](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/234)
- Add support for a 'stroke' around a Polygon [\#235](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/235)
- Deactivate location updates when the map is destroyed [\#236](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/236)

## [4.0.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/4.0.0) (2018-05-07)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.3.0...4.0.0)

**Fixed bugs:**

- Nativescript Mapbox on iOS retain memory after navigation away [\#67](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/67)
- The App crashs on Android when using nativescript-vue - missing toHumanReadableAscii method [\#216](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/216)
- Didn't find class "com.mapbox.mapboxsdk.plugins.locationlayer.LocationLayerPlugin" [\#198](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/198)

**Implemented enhancements:**

- Using/Showing an offline map [\#150](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/150)
- Polygons for iOS [\#204](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/204)
- animateCamera with target increases the zoomLevel to maximum in iOS [\#215](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/215)
- Bump Mapbox iOS SDK to 4.0.0 and Android to 6.0.1 [\#219](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/219)

## [3.3.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.3.0) (2018-01-20)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.2.0...3.3.0)

**Fixed bugs:**

- Console output query [\#177](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/177)

**Implemented enhancements:**

- listOfflineRegions fails on Android if no map has been shown [\#172](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/172)
- How to get lat long of userlocation from mapbox [\#180](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/180)
- Failed to bind EAGLDrawable [\#196](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/196)


## [3.2.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.2.0) (2018-01-13)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.1.3...3.2.0)

**Fixed bugs:**

- Dragging Map [\#175](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/175)
- Don't handle permissions other than our own [\#194](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/194)
- Don't fire the "mapready" event when the style changes [\#195](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/195)

**Implemented enhancements:**

- Is there a way to capture when the map is scrolled? [\136](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/136)
- New Listeners [\#183](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/183)
- Calling selectAnnotation() from native map view throws "TypeError: nv.selectAnnotation is not a function" [\#186](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/186) 
- Bump Mapbox SDK versions [\#193](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/193)


## [3.1.3](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.1.3) (2017-11-02)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.1.2...3.1.3)

**Fixed bugs:**

- Marker onTap - after navigating back to map [\#125](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/125)
- Markers not cleaned from cache on android [\#182](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/182)


## [3.1.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.1.2) (2017-09-12)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.1.1...3.1.2)

**Implemented enhancements:**

- setOnMapClickListener iOS [\#153](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/153)
- Align with the NativeScript plugin seed [\#163](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/163)


## [3.1.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.1.1) (2017-08-24)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.1.0...3.1.1)

**Fixed bugs:**

- Problems with Android that works with iOS [\#162](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/162)


## [3.1.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.1.0) (2017-08-17)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.0.3...3.1.0)

**Implemented enhancements:**

- Feature Request: Update to sdk to 5.1.2+ [\#156](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/156)
- Document the new TRAFFIC_DAY and TRAFFIC_NIGHT styles [\#158](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/158)
- Return the native Mapbox view when show is invoked [\#159](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/159)


## [3.0.3](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.0.3) (2017-08-08)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.0.2...3.0.3)

**Implemented enhancements:**

- Possibility to disable marker tooltip [\#143](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/143)


## [3.0.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.0.2) (2017-08-05)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.0.1...3.0.2)

**Implemented enhancements:**

- Add support for Polyline in IOS [\#41](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/41)
- A desperate request for addPolylines in iOS [\#152](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/152)
- Possibility to disable marker tooltip [\#143](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/143)


## [3.0.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.0.1) (2017-07-12)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/3.0.0...3.0.1)

**Fixed bugs:**

- Icon and OnTap is working only in costructor [\#135](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/135)

## [3.0.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/3.0.0) (2017-04-25)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.6.0...3.0.0)

**XML layout tag changed: Mapbox --> MapboxView**

**Implemented enhancements:**

- NativeScript 3 support [\#104](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/104)

## [2.6.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.6.0) (2017-03-22)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.5.3...2.6.0)

**Make sure you have an up-to-date Android Repository (API level 25) - run `android` in a terminal and update outdated stuff.**

**Implemented enhancements:**

- [Feature request] support getCenter method for XML create maps [\#98](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/98)
- setviewport bounds doesnt work [\#94](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/94)

## [2.5.3](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.5.3) (2017-03-16)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.5.2...2.5.3)

**Implemented enhancements:**

- Added return statement to make the Mapbox.prototype.xxx functions [\#95](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/95)
- Changes to work with XML-based maps #96 [\#96](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/96)
- Changes to work with XML-based maps #97 [\#97](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/97)

## [2.5.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.5.2) (2017-03-04)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.5.1...2.5.2)

**Implemented enhancements:**

- Add a 'destroy' method [\#91](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/91)

**Fixed bugs:**

- Can't download offline region on Android [\#88](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/88)
- Program failed to link at com.mapbox.mapboxsdk.maps.NativeMapView.nativeRender [\#87](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/87)
- Unable to get markers to display [\#86](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/86)
- Cannot read property 'getLocationServices' of undefined [\#80](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/80)

**Closed issues:**

- make sure you add the Telemetry service to your androidManifest.xml [\#90](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/90)
- Custom marker tooltip [\#89](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/89)
- MapBox plugin failing to install on angular-seed-advanced [\#79](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/79)
- Zoom controls [\#76](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/76)

**Merged pull requests:**

- Update AndroidManifest.xml [\#82](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/82) ([Equisetum](https://github.com/Equisetum))
- README.md--Deleted wrong \[\] sintax in setViewport [\#77](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/77) ([seros00](https://github.com/seros00))

## [2.5.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.5.1) (2017-01-29)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.5.0...2.5.1)

**Closed issues:**

- Mapbox dissapear, when call routerExtensions.back\(\) [\#65](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/65)
- iOS Marker added using addMarkers is jumpy when zoomin in/out [\#14](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/14)

## [2.5.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.5.0) (2017-01-29)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.4.0...2.5.0)

**Implemented enhancements:**

- Will the Mapbox Directions api work with Nativescript? [\#28](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/28)

**Closed issues:**

- Can't use the component on Android 4.4.4 or lower [\#66](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/66)
- \[performance\] Move to Mapbox-Android's 5.0 SDK [\#75](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/75)

## [2.4.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.4.0) (2017-01-19)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.3.2...2.4.0)

**Implemented enhancements:**

- user location by xml [\#68](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/68)

**Fixed bugs:**

- user location by xml [\#68](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/68)

**Closed issues:**

- \[IOS\] onCalloutTap event stops working [\#71](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/71)
- MapBox crashing in Android version 7.1.1 [\#63](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/63)
- Automatically handle Android 6+ permissions [\#73](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/73)

**Merged pull requests:**

- Remove markers from internal cache [\#72](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/72) ([vakrilov](https://github.com/vakrilov))

## [2.3.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.3.2) (2017-01-09)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.3.1...2.3.2)

**Fixed bugs:**

- Convert custom url string to NSURL [\#70](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/70) ([ahalls](https://github.com/ahalls))

**Closed issues:**

- Custom Style URL,  Angular2 created in XML crashes on iOS  [\#69](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/69)

## [2.3.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.3.1) (2016-12-05)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.3.0...2.3.1)

**Fixed bugs:**

- Exception on Android with Mapbox in XML [\#62](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/62)
- iOS crash - this.\_mapLoadedCallback is not a function [\#57](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/57)

**Closed issues:**

- Add more ignore  [\#60](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/60)
- Set z-index programatically [\#59](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/59)

**Merged pull requests:**

- Update README.md [\#58](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/58) ([dogabudak](https://github.com/dogabudak))

## [2.3.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.3.0) (2016-11-16)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.2.4...2.3.0)

**Implemented enhancements:**

- Cannot Place UI elements over viewport [\#37](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/37)
- Support for Marker Image URLs [\#20](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/20)

**Fixed bugs:**

- Nativescript Angular 2 issue while using MapBox inside the HTML [\#56](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/56)

**Closed issues:**

- Unable to start activity ComponentInfo:Failed to find module 'Crypto' [\#39](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/39)
- Not show map in demo [\#27](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/27)
- Additional style for Markers [\#23](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/23)

## [2.2.4](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.2.4) (2016-11-16)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.2.3...2.2.4)

**Fixed bugs:**

- Question: marker tap on iOS simulator [\#55](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/55)

**Closed issues:**

- Angular 2 registerElement XML not setting property [\#45](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/45)

## [2.2.3](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.2.3) (2016-11-11)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.2.2...2.2.3)

**Implemented enhancements:**

- Change map style method [\#53](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/53)

**Closed issues:**

- iOS accessToken in XML not working [\#54](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/54)

## [2.2.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.2.2) (2016-11-03)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.2.1...2.2.2)

**Implemented enhancements:**

- Enhancement/Request: timeout when loading XML map [\#52](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/52)

**Merged pull requests:**

- Improve the addPolyline color option [\#50](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/50) ([bradmartin](https://github.com/bradmartin))

## [2.2.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.2.1) (2016-10-26)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.2.0...2.2.1)

**Fixed bugs:**

- onTap/onCalloutTap not working from XML declared map [\#49](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/49)

## [2.2.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.2.0) (2016-10-26)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.1.1...2.2.0)

**Implemented enhancements:**

- Question: remove the polyline [\#47](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/47)
- Allow to use icon path from resource [\#43](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/43)

**Fixed bugs:**

- ShowUserLocation not working [\#31](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/31)
- Request: change Position of Markers without removing them first [\#48](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/48)

**Closed issues:**

- showUserLocation="true" is not working in Android [\#46](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/46)

## [2.1.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.1.1) (2016-10-25)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.1.0...2.1.1)

**Implemented enhancements:**

- Enhancement: expose other methods to XML map [\#44](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/44)

**Closed issues:**

- Does Mapbox measure this plugin's usage as a native app? [\#42](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/42)

## [2.1.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.1.0) (2016-10-15)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/2.0.0...2.1.0)

**Implemented enhancements:**

- Custom Styles In Maps [\#34](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/34)
- Implement FitToBounds [\#21](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/21)

**Fixed bugs:**

- NullPointerException when running on Android [\#3](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/3)

**Merged pull requests:**

- add support for mapbox style URLs [\#38](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/38) ([blinkythebear](https://github.com/blinkythebear))
- Fix null on .show\(\) android [\#30](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/30) ([bradmartin](https://github.com/bradmartin))

## [2.0.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/2.0.0) (2016-10-12)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.5.0...2.0.0)

**Implemented enhancements:**

- Create map as XML element? [\#8](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/8)

## [1.5.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.5.0) (2016-09-23)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.4.0...1.5.0)

**Implemented enhancements:**

- Provide a way to hide and show the map, without redrawing it [\#25](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/25)
- Remove Markers Function [\#19](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/19)

**Fixed bugs:**

- Fixed error adding polylines to map [\#35](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/35) ([devilop3rz](https://github.com/devilop3rz))

**Closed issues:**

- Adding Polylines [\#36](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/36)
- Possible to get street/intersection data? [\#32](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/32)
- \[question\] is it possible to deliver a downloaded map within my app  ? [\#26](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/26)

## [1.4.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.4.0) (2016-08-24)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.3.0...1.4.0)

**Closed issues:**

- How to get Directions / Routes? [\#24](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/24)
- Mapbox not working [\#22](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/22)
- Not working with Angular2/Typescript? [\#9](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/9)

## [1.3.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.3.0) (2016-07-18)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.2.1...1.3.0)

## [1.2.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.2.1) (2016-07-09)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.2.0...1.2.1)

## [1.2.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.2.0) (2016-07-08)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.1.2...1.2.0)

**Implemented enhancements:**

- Add click event on marker [\#6](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/6)

**Closed issues:**

- Offline and Element overlay capability question [\#13](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/13)
- Mapbox-4.0.0 : Can't add a marker : markerOptions.title is not a function [\#12](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/12)
- Unable to start activity ComponentInfo{org.nativescript.mapboxdemo/com.tns.NativeScriptActivity} [\#7](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/7)

**Merged pull requests:**

- Mapbox 4.0.0 [\#18](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/18) ([EddyVerbruggen](https://github.com/EddyVerbruggen))
- Add Polyline function [\#11](https://github.com/EddyVerbruggen/nativescript-mapbox/pull/11) ([Neomac](https://github.com/Neomac))

## [1.1.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.1.2) (2016-03-16)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.1.1...1.1.2)

**Closed issues:**

- 'Zoom' attribute error [\#4](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/4)

## [1.1.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.1.1) (2016-02-04)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.1.0...1.1.1)

## [1.1.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.1.0) (2016-02-04)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.0.5...1.1.0)

**Closed issues:**

- Empty black box on iOS [\#1](https://github.com/EddyVerbruggen/nativescript-mapbox/issues/1)

## [1.0.5](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.0.5) (2015-12-22)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.0.4...1.0.5)

## [1.0.4](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.0.4) (2015-11-03)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.0.2...1.0.4)

## [1.0.2](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.0.2) (2015-10-28)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.0.1...1.0.2)

## [1.0.1](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.0.1) (2015-10-08)
[Full Changelog](https://github.com/EddyVerbruggen/nativescript-mapbox/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/EddyVerbruggen/nativescript-mapbox/tree/1.0.0) (2015-10-03)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
