# Current loop interface

These are "as-built"; components were to hand, there are many better ways to do this.

An example of someone doing it better: http://heepy.net/mediawiki/index.php/Optocouplers_for_teletype_current_loop

Current status: untested, not sure it works.

Alternative designs would include:

* Off-the-shelf RS232 convertor, then level-conversion for RS232 to microcontroller.  For example the [B&B](www.bb-elec.com/Products/Serial-Connectivity/Serial-Converters/Current-Loop-Converters.aspx) series.
* Solid-state relays instead of low-voltage optoisolators.  Essential when driving older teletype machines on 60mA/120V current loop. See for example: http://www.aetherltd.com/connecting.html. 





