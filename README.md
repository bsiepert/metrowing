# metrowing
A an adapter to use Adafruit featherwings with Adafruit Metros or Arduino Unos

[BOM on Octopart](https://octopart.com/bom-tool/s72yPqrf)

mkii fixes/updates:
* Adds a SPI header so that we can pick up the SPI/ICSP header on the Metro and route MOSI/MISO/SCK to the appropriate FeatherWing pins. A female ICSP header should be mounted *underneath* the featherwing so that it can plug into the male ICSP header on the Metro. This will allow for use of the LoRa feathers and others that need SPI
* Routes the Metro's +5v to the USB power rails on the feather for Wings that need more juice like the NeoPixel Featherwing
* Adjusts header locations for better clearance
* Fixes pin labels 
* Changes Reset button
* Added 15 pieces of flair

As of 11/15/17 this version is untested
