# OpenAL-SpatialMixer

Apple deprecated the 3DMixer-based OpenAL.framework in macOS 10.15 and tossed out the one in iOS 9 SDK. What if we can just make it use SpatialMixer instead?

* [ ] plumb to `kAudioUnitSubType_SpatialMixer` - probably remove 3DEM version code, then idk
* [ ] plumb to work on iOS... simulator
* [ ] plumb to use some panner magic on desktop
* [ ] extensions, lmao
