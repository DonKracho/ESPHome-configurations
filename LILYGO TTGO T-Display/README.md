## LILYGO® TTGO T-Display

This ESP32 display module is quite old already.  Time to create a basic ESPHome configuration.
This example prints some Home Assistant sensor values to the diaplay corners and a text given in the text fied to the center of the display.
The display content gets rotated by 90°.

Pressing the lower button draws some graphics primitives using the ESPHome display functions instead.
Pressing the upper button puts the devise into sleep mode. Wake up the device again by pressing the lower button.

To get real and valid sensor values you will have up update the homesaaistant sensor entity_ids.

NOTE: The Home Assistant sensor values can be shown only after api connection has been estabished by adding the mdule to the Home Assistant instance.
