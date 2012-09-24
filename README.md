README: nfc-starter-apps 
================

This repo contains 3 starter apps to kick off your NFC development for Android.

These apps were originally created for [Professional Android Sensor Programming](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118183487.html) written by Greg Milette & Adam Stroud and published by Wrox Press, then forked from the book's [Great Android Sensing Toolkit (GAST)](https://github.com/pchen/gast-lib) library. I am the contributing author of _Chapter 11: Near Field Communication (NFC)_ and a contributing co-author for _Chapter 10: Android Open Accessory_.


## How to get started with NFC development

* In Eclipse, use the **File > Import > Existing Projects into Workspace ** option to import individual or all app projects into the current Eclipse workspace.

**Simple NFC Inventory:** Shows off basic reading and writing of NFC tags using NDEF formatting. Works on Gingerbread devices and up.

**P2P NFC Inventory:** Builds off of SimpleNFCInventory by adding peer-to-peer support. Use this for pre-ICS devices (e.g. Gingerbread), otherwise use BeamNFCInventory.

**Beam NFC Inventory:** Builds off of SimpleNFCInventory by adding peer-to-peer support using the new ICS (Android 4.0) Beam APIs.

## To learn more about NFC

+ Read the book: [Professional Android Sensor Programming](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118183487.html) (Note: Does not cover any new NFC features included in Jelly Bean since it was published before Google I/O 2012.)
+ Flip through a non-technical and [short presentation on NFC](http://prezi.com/-nn2gofxtjmf/nfc-beyond-mobile-payments/) that I created for FITC: Toronto 2012
+ Keep an eye out for another [Peanut Butter & Code Jam](http://pbcj.eventbrite.com) focussed on NFC or Android.
+ I also do full-day workshops like [this one](http://www.fitc.ca/events/presentations/presentation.cfm?event=134&presentation_id=2057) for FITC SCREENS 2012
+ For news on upcoming workshops and events, you can [sign up for my mailing list](http://eepurl.com/ousKX). I can also do private/corporate training -- please contact me if you are intersted!

## Contact

+ [Google+](http://klab.ca/+)
+ [Twitter](http://twitter.com/androidsNsheep)
+ Email me via pearl[at]karma-laboratory.com

## License

All the code is licensed under the Apache 2.0 license. See [LICENSE.txt](https://github.com/pchen/nfc-starter-apps/blob/master/LICENSE.txt) for license details.
