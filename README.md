# SmartCampus
Проєкт SmartCampus створений на основі Home Assistance.

Система оповіщення та моніторингу для навчального корпусу.

Функціональні можливості:
- сповіщення про тривоги;
- інформаційні повідомлення;
- моніторинг параметрів мікроклімату.

![image](https://github.com/user-attachments/assets/382ec1c4-feb8-41a9-89f5-aa9a898c38f8)
Структурна схема пристрою оповіщення:
1 – мікроконтролерна плата ESP32; 2 – підсилювач звуку MAX98357A; 3 – динамік; 
4 – модуль моніторингу параметрів мікроклімату BME280; 5 – датчик освітленості ТЕМТ6000; 
6 – датчик якості повітря MQ-135; 7 – роз’єм живлення.

Пристрої оповіщення підключені до існуючої мережі WiFi навчального корпусу і через неї комунікують з сервером де розгорнуто програмне забезпечення управління системою 

![image](https://github.com/user-attachments/assets/5dc682d6-ecec-46c9-b937-1337aff28d25)


Довідкові матеріали:
- Home Assistant https://www.home-assistant.io/
- ESPHome https://esphome.io/
- медіапрогравач https://bootuse.com/2023/06/23/esphome-esp32-max98357a-i2s/
- використання сенсора BME280 в ESPHome https://esphome.io/components/sensor/bme280
- використання сенсора TEMT6000 в ESPHome https://devices.esphome.io/devices/temt6000

