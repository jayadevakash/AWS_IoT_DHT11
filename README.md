# AWS_IoT_DHT11
Log the DHT11 Temperature sensor data to the AWS IoT.

Things you need:
1. AWS account.
2. Raspberry Pi 0/1/2/3
3. DHT11 (Temperature Sensor)
4. Bitvise SSH Client

Things to do:
1. Run the RPi with UbuntuMate or jessie or Ubuntu.(Enable the SSH)
2. Create a thing in the AWS IoT Core. Follow this link for help: https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html
3. Transfer the downloaded certificates to the RPi.
4. Things to install:
      (i). pip install paho-mqtt
     (ii). pip install AWSIoTPythonSDK
5. Also download: https://github.com/szazo/DHT11_Python
