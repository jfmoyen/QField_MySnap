# QField_MySnap
A modified version of the snap! plugin to support saving to pre-defined layers

QField is a portable version of QGIS. I am using it for geological mapping, using a suite of tools to tweak the functionalities to the specific needs of this activity:
- A QGIs project and database template ([here](https://github.com/jfmoyen/QField_Geological_mapping_template/));
- A plugin adding a geological compass to measure and record planes and lines ([here](https://github.com/jfmoyen/QField_qml_Geological_compass)), adapted from [Mark Jessel's work](https://github.com/swaxi/compass);
- A plugin streamlining the use of camera ([you are here!](https://github.com/jfmoyen/QField_MySnap)), modified from [QField plugin Snap!](https://github.com/opengisch/qfield-snap)

  The three tools can be used independently. Together, they offer a platform that works well (at least, for me) in the field. A source of inspiration for this project is the [FieldMove]((https://www.petex.com/products/move-suite/digital-field-mapping/)) application: the first goal was to reproduce FieldMove's functionalities, but adding the flexibility and "openness" of QField.

## Changes to the Snap! plugin

The [Snap! plugin](https://github.com/opengisch/qfield-snap) adds a button to the interface to automatically take a photo and save to the *active* layer. This version is exactly the same with one change: through the plugin options, you can select in advance the layer that will be used to save the photos (even if it is not currently active).

The settings can be accessed via the normal plugin setting options:
1. Open the Side Dashboard and tap the three dots icon to open Settings.
2. Tap Plugins
3. Next to the plugin name, tap on the settings button

of with a long press on the Snap! button in the main interface.

## Download and install

Like all [QField plugins](https://docs.qfield.org/how-to/advanced-how-tos/plugins/#application-plugins), you can do any of the following:
1. Download manually the plugin files and copy them to the `Android/data/ch.opengis.qfield/files/QField/plugins/mySnap` of your (Android) device (iOS users, locate the plugin directory and copy the files there!)
2. Install from url using the following url: https://github.com/jfmoyen/QField_MySnap/blob/main/QField_MySnap.zip
3. Install by scanninng this QRCode (this is a shortcut to the same url):
<img src="img/qr-code.jpg" width="300" height="300">

In any case, do not forget to activate the plugin (go to the side dashboard -> 3 dots menu -> plugins -> local plugins -> activate using the switch)

<img src="img/plugin_menu.png" width="400" height="600">