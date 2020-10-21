# visx-sdk-android

## About VIS.X® SDK for Android

VIS.X® is a new and unique kind of advertising technology that enables efficient execution of media and high-impact ad products at scale. VIS.X® wraps the inventory in a holistic auction offering all available products in one transaction to buyers, consequently optimizing the bidstream. YOC has developed this platform to unlock the real value of digital advertising – making VIS.X® the go-to-platform for high-impact programmatic advertising. VIS.X® SDK for Android offers publisher access to high-impact programmatic advertising on in-app inventory.

## Technical Documentation

The full documentation is available __[here](https://support.yoc.com/)__.

## Change Log
### VIS.X SDK for Android v1.1
##### New Features
* Interstitial: Is now controlled via additional flag on the AdSize and no longer dependent to a specific size
* Inline Placements are UniversalAds per default
* Introduction of .prefetchAd() as option for VisxAdView to decouple request and rendering of Ads
* Using mraid.open() will open the landing page in in-app browser per default in a modal view
##### Bug Fixes:
* Fixed Memory Leaks
* AdItem is no longer obfuscated
* Fixed issues with mraid.resize(), mraid.expand()
* Fixed audio issues related for *"YOC Inline Video Ad"*
