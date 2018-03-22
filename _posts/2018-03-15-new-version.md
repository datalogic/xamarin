---
layout: post
title: SDK Version 1.8.89 is now available
date: 2018-03-15 11:00:00 +0100
---

**Version 1.8.89** is now available for download. Follow the directions on the <a href="{{ site.baseurl }}/quick-start">Quick Start</a> page to get started. You can also download directly from <a href="https://www.nuget.org/packages/datalogic-xamarin-sdk/1.8.89">NuGet here</a>.


#### Support all Datalogic Android SDK 1.6,1.7,1.8 features:


* Multi Scan
* Character set support for certain 2D symbologies:
 * Aztec
 * Data Matrix
 * Micro PDF417
 * Micro QR code
 * PDF417
 * QR code


* Composite symbology support
* Web Wedge functionality
* GS1 DataBar conversion to GS1-128


* Linear quiet zone configuration, only EAN/UPC for now
* EAN-13 send system digit configuration



#### Known issues:
* 61034: Program may crash when calling SoftSpot.SetImage()
* 61027: GetPropertyAvailability(emptyList, availabilityBuffer) returns Error, when it should return SUCCESS

#### API changes:


##### Added public classes
{% include x-link.html uri='T.Com.Datalogic.Decode.Configuration.Composite' %}
{% include x-link.html uri='T.Com.Datalogic.Decode.Configuration.LinearQuietZones' %}
{% include x-link.html uri='T.Com.Datalogic.Decode.Configuration.MultiScan' %}
{% include x-link.html uri='T.Com.Datalogic.Decode.Configuration.WebWedge' %}


##### Added public interfaces


##### Added public methods

{% include x-link.html uri='M.Com.Datalogic.Decode.Configuration.CharacterSetMode#ValueOf' %}
{% include x-link.html uri='M.Com.Datalogic.Decode.Configuration.CharacterSetMode#Values' %}
{% include x-link.html uri='M.Com.Datalogic.Decode.Configuration.UpcEanCompositeMode#ValueOf' %}
{% include x-link.html uri='M.Com.Datalogic.Decode.Configuration.UpcEanCompositeMode#Values' %}



##### Added public fields

{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#AztecCharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#CompositeEanUpcMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#CompositeEnable' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#CompositeGs1128Mode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#CompositeUserId' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#DatamatrixCharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Ean13SendSys' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Gs114Gs1128Mode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Gs1ExpGs1128Mode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Gs1LimitGs1128Mode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Micropdf417CharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#MicroQrCharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#MultiscanEnable' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#MultiscanNotificationEnable' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#MultiscanRequiredLabels' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#Pdf417CharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#QrcodeCharacterSetMode' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#UpcEanShortQuietZones' %}
{% include x-link.html uri='F.Com.Datalogic.Decode.PropertyID#WedgeWebEnable' %}





##### Added public properties


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Composite#ConvertToGs1128' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Composite#UpcEanMode' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Datamatrix#CharacterSetMode' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Ean13#SendSystemDigit' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Gs1DataBar_14#ConvertToGs1128' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Gs1DataBar_Expanded#ConvertToGs1128' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Gs1DataBar_Limited#ConvertToGs1128' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.LinearQuietZones#UpcEanReduced' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Micropdf417#CharacterSetMode' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Micropdf417#CharacterSetMode' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.MultiScan#Enable' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.MultiScan#LabelCount' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.MultiScan#NotifyOnEachLabel' %}




{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.Pdf417#CharacterSetMode' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.QRCode#CharacterSetMode' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.ScannerProperties#Composite' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.ScannerProperties#LinearQZ' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.ScannerProperties#MultiScan' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.ScannerProperties#WebWedge' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.WebWedge#Enable' %}


{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeCcA' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeCcB' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1128A' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1128B' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1128C' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs114A' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs114B' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1ExpA' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1ExpB' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1LimitA' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.BarcodeID#CompositeGs1LimitB' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Symbology#Composite' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Big5' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#EucCn' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#EucKr' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Gb18030' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Gbk' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Ibm437' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88591' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso885911' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso885914' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso885915' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88592' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88593' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88594' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88595' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88596' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88597' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88598' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Iso88599' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#ShiftJis' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#UsAscii' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Utf16' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Utf8' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Windows1250' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Windows1251' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Windows1252' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Windows1254' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.CharacterSetMode#Windows1256' %}

{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.UpcEanCompositeMode#AlwaysLinked' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.UpcEanCompositeMode#Auto' %}
{% include x-link.html uri='P.Com.Datalogic.Decode.Configuration.UpcEanCompositeMode#NeverLinked' %}




##### Changed public fields

Updated version from 1.5 to 1.8.
{% include x-link.html uri='F.Com.Datalogic.Device.Info.SYSTEM.Version#SdkVersionMinor' %}




 

