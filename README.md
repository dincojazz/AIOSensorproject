# AIOSensor
Created own AIOSensor with lot of Home Assistant forum help.

The hardware components are:
ESP32C3mini, LD2410b, BH1750 and BME680

1. ESP32-C3 SuperMini Development Board from AliExpress for 3.38$
   https://www.aliexpress.com/item/1005005967641936.html?spm=a2g0o.order_list.order_list_main.58.d59718021g5CO2
   ![ESP32 C3 SuperMini Pinout Front](https://github.com/dincojazz/AIOSensor/assets/75685324/792156eb-cbbc-4581-8bee-5a9d9580b4b3)
   ![ESP32 C3 SuperMini Pinout Back](https://github.com/dincojazz/AIOSensor/assets/75685324/8013fa68-faa0-4d12-86d2-228c4ac94474)
2. LD2410b Mini HLK-LD2410B High Sensitivity 24G Human Presence Status Radar Heartbeat Detection Sensor
   https://www.aliexpress.com/item/1005004920357733.html?spm=a2g0o.order_list.order_list_main.362.69b21802IY6zQK
   ![LD2410b front](https://github.com/dincojazz/AIOSensor/assets/75685324/54c37b2b-1274-4e81-ada4-80220cf0eafe)
   ![LD2410b back](https://github.com/dincojazz/AIOSensor/assets/75685324/d5a69fcf-8f67-4c6a-bfdc-31c8689722a4)
3. BME680 Digital Temperature Humidity Pressure Sensor CJMCU-680 High Altitude Module Development Board from AliExspress for 5.15$
   https://www.aliexpress.com/item/4001113450307.html?spm=a2g0o.order_list.order_list_main.297.69b21802IY6zQK
   ![BME680 data](https://github.com/dincojazz/AIOSensor/assets/75685324/a5d2cc4b-fd9e-4c1f-945c-1cfb41cfcc88)
   ![BME680 front](https://github.com/dincojazz/AIOSensor/assets/75685324/861d98dc-b9a3-4516-9f4c-aba0742f6ca3)
   ![BME680 back](https://github.com/dincojazz/AIOSensor/assets/75685324/f402f16e-0c3d-4064-93fd-d113ae445d2a)
4. BH1750 GY-302 light intensity illumination module from AliExpress for 0.67$
   https://www.aliexpress.com/item/1005001572932920.html?spm=a2g0o.order_list.order_list_main.189.69b21802IY6zQK
   ![BH1750 data](https://github.com/dincojazz/AIOSensor/assets/75685324/6f8199d2-d084-4c48-803d-f5339330f394)
   ![BH1750 front](https://github.com/dincojazz/AIOSensor/assets/75685324/cd7695a2-bfaa-458f-9ee8-4b039b852a14)
   ![BH1750 back](https://github.com/dincojazz/AIOSensor/assets/75685324/ec12b1a3-b6b4-4f12-9b50-7e1da86fad59)
and
5. Power for BME680 module
   High Quality 5V To 3.3V For DC-DC Step-Down Power Supply Buck Module AMS1117 LDO 800MA from AliExpress for 0.121$
   https://www.aliexpress.com/item/1005003678235693.html?spm=a2g0o.order_list.order_list_main.241.69b21802IY6zQK
   Specifications:
   Input: DC4.5V-7V
   The input voltage must be more than 1V higher than the output voltage
   Output: 3.3V 800mA
   The load current can be constant in excess of 800mA
   Module size: 8.6mm*12.33mm
   With power indicator, 1.2V low dropout.
   The input is only 1.2V above the output to operate normally
   ![AMS1117 LDO 800MA front](https://github.com/dincojazz/AIOSensor/assets/75685324/1630623a-41e4-43f6-b39a-c2f299758d32)
   ![AMS1117 LDO 800MA back](https://github.com/dincojazz/AIOSensor/assets/75685324/e508898c-d46c-47c6-8572-d93146bb5322)
6. Added DIY voltage divider with MOSFET BSS138  for battery measurment.
   From middle point between two 2.2MΩ resistores connecting to ESP32-C3's ADC on GPIO1 to measure battery voltage.
   From ESP32-C3's GPIO2 connecting to 10KΩ resistor to control MOSFET for measuring cicle.
   ![Voltage Divider MOSFET](https://github.com/user-attachments/assets/6f7db0fe-f496-424d-999f-a0a8db6def1a)



