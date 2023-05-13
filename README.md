# temp_humidity-monitor
In this , we can connect the ESP8266 with AWS IoT Core & publish sensor reading to AWS MQTT. 
We will use the DHT11 Sensor and read the humidity temperature data. 
The NodeMCU ESP8266 will connect to the local WiFi network and will post the DHT11 Sensor data to AWS IoT Cloud. 
Not only posting data, but we can also receive the data from AWS Dashboard. 

Steps involved:
1. Signing up & setting the Amazon Web Services
2. Installing Necessary Libraries to Arduino IDE & Writing an Arduino Sketch for the project
3. Creating a Thing is AWS
4. Creating Policy and attaching to Thing
5. Generating Certificates
6. Modifying Arduino Sketch according to Thing Data & Credentials
7. Subscribe & Publish Data to and from AWS Dashboard


![image](https://github.com/priyadharshini1250/temp_humidity-monitor/assets/90914294/e5ed15c2-9bb1-4a29-916b-b1fb9549b99f)
