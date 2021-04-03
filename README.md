# iot with arduino iot with arduino mkr wifi 1010

### 0, arduino libs: https://github.com/arduino-libraries
### 101, basic setup: https://www.arduino.cc/en/Guide/MKRWiFi1010
### 102, gen private key and CSR and connect to aws iot: https://create.arduino.cc/projecthub/Arduino_Genuino/securely-connecting-an-arduino-mkr-wifi-1010-to-aws-iot-core-a9f365 ** don't need to worry about locking ATECC508A to ECC608A crypto element as it doesn't lock data content and you can override it: https://forum.arduino.cc/index.php?topic=609739.0

### aws side of the story on device connection, https://docs.aws.amazon.com/iot/latest/developerguide/iot-connect-devices.html

### how to build arduino lib, https://roboticsbackend.com/arduino-create-library/#:~:text=Simply%20open%20the%20Arduino%20IDE,t%20need%20to%20restart%20it.

### flow
#### device <-> MQTT Broker <-> AWS iot rules engine -> 



Beside AWS, there are other similar providers, eg. Zapier, Arduino, 
check out the tutorial: https://create.arduino.cc/projecthub/Arduino_Genuino/plant-communicator-with-mkr-wifi-1010-efc920

