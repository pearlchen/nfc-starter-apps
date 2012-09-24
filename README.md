nfc-starter-apps
================

This repo contains 3 starter apps to kick off your NFC development for Android.

These apps were originally created for [Professional Android Sensor Programming](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118183487.html) written by Greg Milette & Adam Stroud and published by Wrox Press, then forked from the book's [Great Android Sensing Toolkit (GAST)](https://github.com/pchen/gast-lib) library. I am the contributing author of _Chapter 11: Near Field Communication (NFC)_ and a contributing co-author for _Chapter 10: Android Open Accessory_.


## How to get started with development

* Unzip each individual project archive. In Eclipse, use the **File > Import > Existing Projects into Workspace ** option in Eclipse to import individual app projects into current Eclipse workspace.

SimpleNFCInventory.zip: Shows off basic reading and writing of NFC tags using NDEF formatting. Works on Gingerbread devices and up.

P2PNFCInventory.zip: Builds off of Simple NFC Inventory by adding peer-to-peer support. Use this for pre-ICS devices (e.g. Gingerbread), otherwise use BeamNFCInventory.zip.

BeamNFCInventory.zip: Builds off of Simple NFC Inventory by adding peer-to-peer support using the new ICS (Android 4.0) Beam APIs.

## To learn more about NFC

+ Read the book: [Professional Android Sensor Programming](http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118183487.html)
+ Flip through a non-technical and [short presentation on NFC](http://prezi.com/-nn2gofxtjmf/nfc-beyond-mobile-payments/) that I created for FITC: Toronto 2012
+ Keep an eye out for another [Peanut Butter & Code Jam](http://pbcj.eventbrite.com) focussed on NFC or Android.

## Contact

+ [Google+](http://klab.ca/+)
+ [Twitter](http://twitter.com/androidsNsheep)
+ Email me via pearl[at]karma-laboratory.com

## License

All the code is licensed under the Apache 2.0 license. See [LICENSE.txt](https://github.com/pchen/nfc-starter-apps/blob/master/LICENSE.txt) for license details.
