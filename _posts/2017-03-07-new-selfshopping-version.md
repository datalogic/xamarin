---
layout: post
title: SDK Self-shopping Extension, version 1.1.6-alpha now available
date: 2017-03-07 11:00:00 +0100
---

**Version 1.1.6-alpha** is now available for download. Follow the directions on the <a href="{{ site.baseurl }}/quick-start">Quick Start</a> page to get started. You can also download directly from <a href="https://www.nuget.org/packages/datalogic-xamarin-sdk-selfshopping/1.1.6-alpha">NuGet here</a>.

### Fixes and other changes:
- Fixed a bug that resulted in an <code>InvalidCastException</code> when casting <code>CradleManager.JTCradle</code>. i.e.:

    <code>ICradleJoyaTouchCradle jtc = (ICradleJoyaTouch)CradleManager.JTCradle;</code>




