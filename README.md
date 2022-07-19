# esp32_connected_hive
esp32 prog for connected hive measurements

Connected beehive balance measuring weight, hive temp, outdoor temp et humidity. 
Connect to remote view webapp to be implemented on raspberry pi. 
Data trasnfer through GSM. 

The data are sent from hive balance to remote raspberry app. see other part of project. 
In case of sudden loss of weight, the balance send an alert to owner cellphone(swarming alert) 


# Hardware: 
- esp32 
- 4 load cell + HX711 amplifier
- DHT11 sensor for outdoor mesaurements
- water proof DS1820 sensor for internal mesaure
- GSM sim 800L EVB module + sim 

