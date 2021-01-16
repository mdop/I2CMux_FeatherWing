# I2CMux FeatherWing

This project is a shield for Adafruits 'Feather' delelopment board series. It is designed to provide 6 STEMMA Qt and 2 STEMMA/STEMMA Qt (or equivalent) I2C outputs which can be set to 2 different voltage levels.

**Suggested Applications**
* Use 5V only sensors with Feather-boards
* Utilize multiple I2C gadgets with same address

**Features**
* Can connect up to 8 I2C gadgets with identical address.
* I2C Channels 0-3 and 4-7 and their respective power can be independently set to voltage levels 3.3V/V_USB/V_BAT
* Channel 1-3 and 5-7 have JST-SH headers compatible with STEMMA Qt and compatible devices without adapter. Channel 0 and 4 can be connected to a JST-PH (STEMMA format) or SH header, both footprints are available.
