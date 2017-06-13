---
layout: post
title: SDK Version 1.4.77-beta now available 
date: 2017-03-09 11:00:00 +0100
---
**Version 1.4.77-beta** is now available for download. This version of the SDK includes all features in the Datalogic Android SDK version 1.4. Follow the directions on the <a href="{{ site.baseurl }}/quick-start">Quick Start</a> page to get started. You can also download directly from <a href="https://www.nuget.org/packages/datalogic-xamarin-sdk/1.4.77-beta">NuGet here</a>.



### Support all Datalogic Android SDK 1.4 features:

- The change is important in order to be fully compatible with new linear scan engines (such as Tungsten). It means certain properties, at runtime, will be reported as available or not, through the IsSupported method.

- For the same reason the PropertyGroup (used by most of the decoding classes) exposes now two methods:

{% include xamarin-man-link.html uri='P.Com.Datalogic.Device.Configuration.PropertyGroup#IsFullySupported' %} 

Tells if this property group is completely supported by the underling decoding hardware
 
 
{% include xamarin-man-link.html uri='P.Com.Datalogic.Device.Configuration.PropertyGroup#IsSupported' %}

Tells if this property group is supported by the underling decoding hardware (at least one property is available)


- You can query the availability on each single configurable attribute of the class (once you discover the whole group is not fully supported)

- Show documentation when viewed in 'Object Browser' in Visual Studio (include XML documentation in nuspec file).

- Added <code>uses-library</code> to AssemblyInfo.cs. This way, you don't have remember to add it in your own projects that use the Datalogic Xamarin SDK.

### Fixes and other changes:
- Decoding properties (for example, <code>Com.Datalogic.Decode.Configuration.Aztec.IsSupported())</code> fixed to correcty report correct status on different platforms.

### API changes:

**Added methods:**
{% include xamarin-man-link.html uri='M.Com.Datalogic.Decode.BarcodeDefaults#GetPropertyAvailability' %}
{% include xamarin-man-link.html uri='M.Com.Datalogic.Decode.BarcodeDefaults#GetPropertyRanges' %}  

{% include xamarin-man-link.html uri='M.Com.Datalogic.Decode.BarcodeManager#GetPropertyAvailability' %}
{% include xamarin-man-link.html uri='M.Com.Datalogic.Decode.BarcodeManager#GetPropertyRanges' %}    

{% include xamarin-man-link.html uri='M.Com.Datalogic.Device.Configuration#GetPropertyAvailability' %}
{% include xamarin-man-link.html uri='M.Com.Datalogic.Device.Configuration#GetPropertyRanges' %}    

{% include xamarin-man-link.html uri='M.Com.Datalogic.Device.Configuration.PropertyGroup#IsFullySupported' %}    

