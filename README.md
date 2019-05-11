# TempSensor-udoo-homebridge-HomeKit

For UDOO plaform only:
Install the homebridge-HTTP-TEMPERATURE plugin

Then add the accessory to config.json as below:

"accessory": "HTTP-TEMPERATURE",
"name": "JY_Living Room Temp",
"getUrl": "http://localhost/showtemp.php",
"pullInterval" : 5000

create the showtemp.php

restart the homebridge and will start to getting the room temperature
