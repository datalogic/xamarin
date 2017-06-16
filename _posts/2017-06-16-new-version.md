---
layout: post
title: SDK Version 1.5.88-beta now available
date: 2017-06-16 11:00:00 +0100
---

**Version 1.5.88-beta** is now available for download. Follow the directions on the <a href="{{ site.baseurl }}/quick-start">Quick Start</a> page to get started. You can also download directly from <a href="https://www.nuget.org/packages/datalogic-xamarin-sdk/1.5.88-beta">NuGet here</a>.


#### Support all Datalogic Android SDK 1.5 features:
* Added Digimarc configuration
* Added new SoftSpot Apis
* Added Trigger selection/configuration
* Added IsKeyDisasbled to KeyboardManager
* Added AutoScan as a configurable WakeupSource


#### Known issues:
* 61034: Program may crash when calling SoftSpot.SetImage()
* 61027: GetPropertyAvailability(emptyList, availabilityBuffer) returns Error, when it should return SUCCESS

#### API changes:


##### Added public classes
{% include x-link.html uri='T.Com.Datalogic.Decode.Configuration.Digimarc' %}
{% include x-link.html uri='T.Com.Datalogic.Device.Input.AutoScanTriggerRange' %}
{% include x-link.html uri='T.Com.Datalogic.Softspot.ActionType' %}
{% include x-link.html uri='T.Com.Datalogic.Softspot.DecodedDuration' %}
{% include x-link.html uri='T.Com.Datalogic.Softspot.ImageEnum' %}
{% include x-link.html uri='T.Com.Datalogic.Softspot.ImageState' %}


##### Added public interfaces
{% include x-link.html uri='T.Com.Datalogic.Device.Input.IAutoScanTrigger' %}
{% include x-link.html uri='T.Com.Datalogic.Device.Input.ITrigger' %}


##### Added public methods

{% include x-link.html uri='M.Com.Datalogic.Device.Input.KeyboardManager#IsKeyDisabled' %}
{% include x-link.html uri='M.Com.Datalogic.Softspot.SoftSpot#GetImage' %}
{% include x-link.html uri='M.Com.Datalogic.Softspot.SoftSpot#Lock' %}
{% include x-link.html uri='M.Com.Datalogic.Softspot.SoftSpot#SetDecodedDuration' %}
{% include x-link.html uri='M.Com.Datalogic.Softspot.SoftSpot#SetImage' %}
{% include x-link.html uri='M.Com.Datalogic.Softspot.SoftSpot#SetVibrator' %}

##### Added public fields
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#DigimarcEnable' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Configuration.ConfigException#SupportError' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager#TriggerIdAutoscan' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager#TriggerIdFront' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager#TriggerIdLeft' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager#TriggerIdPistol' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager#TriggerIdRight' %}
{% include x-link.html uri='F.Com.Datalogic.Device.Input.KeyboardManager.VScanCode#VscanAutoscanTrigger' %}


##### Added public properties
{% include x-link.html uri='P.Com.Datalogic.Softspot.SoftSpot#LockState' %}
{% include x-link.html uri='P.Com.Datalogic.Device.Input.KeyboardManager#AvailableTriggers' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Symbology#Digimarc' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.ScannerProperties#Digimarc' %}
{% include x-link.html uri='P.Com.Datalogic.Device.Power.WakeupSource#TrigAutoscan' %}

##### Changed public fields

Updated version from 1.4 to 1.5.
{% include x-link.html uri='F.Com.Datalogic.Device.Info.SYSTEM.Version#SdkVersionMinor' %}




 

