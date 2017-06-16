---
layout: post
title: SDK Self-shopping Extension version 1.2.15-beta now available
date: 2017-06-16 11:00:00 +0100
---

**Version 1.2.15-beta** is now available for download. Follow the directions on the <a href="{{ site.baseurl }}/quick-start">Quick Start</a> page to get started. You can also download directly from <a href="https://www.nuget.org/packages/datalogic-xamarin-sdk-selfshopping/1.2.15-beta">NuGet here</a>.

#### Support all Datalogic Android SDK Self-shopping Extension 1.2 features:
* Enhanced cradle insertion tracking
* Support Cradle LED dimming, actions, persistence and events

#### API changes:

##### Added public classes:

{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.DimmingSequence' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.DimmingSequencePoint' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.SelfshoppingLedManager' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedAction' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedActionBlink' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedActionDim' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedActionSetBrightness' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedActionTurnOff' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.LedActionTurnOn' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Action.Persistence.PersistJSON' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.Event.ILedEvent' %}

##### Added public interfaces:

{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Cradle.ICradleInsertionListener' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.IDimmingLed' %}
{% include s-link.html uri='T.Com.Datalogic.Extension.Selfshopping.Led.ILed' %}

##### Added public methods:

{% include s-link.html uri='M.Com.Datalogic.Extension.Selfshopping.Cradle.ICradle#AddCradleInsertionListener' %}
{% include s-link.html uri='M.Com.Datalogic.Extension.Selfshopping.Cradle.ICradle#RemoveCradleInsertionListener' %}

##### Changed public fields:

Updated API version from 1.1 to 1.2.
{% include s-link.html uri='F.Com.Datalogic.Extension.Selfshopping.Version#SelfshoppingExtensionVersion' %}
{% include s-link.html uri='F.Com.Datalogic.Extension.Selfshopping.Version#SelfshoppingExtensionVersionInt' %}




