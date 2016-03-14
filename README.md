# Heartbox Overview
Connect a blinking LED heart to an ESP8266 (01) to be able to tell/show a loved one you're thinking of them.

## Contents
Currently just the .ino file (sketch). Can find parts tutorial, inventory, etc. on my upcoming hackster.io post 

### Require changes to sketch
-  ssid
-  password
-  title for page (if you wish to change what the webserver's index page shows, "Blinking Heart Box" is default)
-  name of device (heartbox is default)
-  gpio pin to control (2 is default)

#### Operation
-  download the [ESP8266](https://github.com/esp8266/Arduino) libraries
-  download the [aREST](https://github.com/marcoschwartz/aREST) and [aREST_UI](https://github.com/marcoschwartz/aREST_UI) libraries
-  modify the heartbox.ino sketch (substitute your info from the "Required Changes" section)
-  upload the heartbox.ino sketch to your ESP8266
-  browse to "name".local or observe ip in serial output in serial monitor
-  test button operation by connecting something to the GPIO pin indicated in the sketch
