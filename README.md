# **THIS REPOSITORY IS OFFLINE**

# ESP8266 Projects

## Introduction
I had some free time and was bored when I heard about the ESP devices. I decided to order one myself (NodeMCU ESP8266 V3 CH340G). This is a little "library" of my different projects.  
Every project has it's own folder with a binary (.bin) file and the Arduino sketch.  
If you do not want to modify the firmware you can flash it on your ESP with the **.bin** file using a flasher like [**esp.huhn.me**](https://esp.huhn.me).

**Note**: Please remember that you need **Arduino** as long as you want to modify the different projects!  

### ESP8266 WebServer LED project
You can find this project in the "**ESP8266WebServer_LED_Controller**" of this repository.  
This program will create an Access Point called "**ESP_WebServer**" with the password "**12345678**" when flashed on your ESP 8266. Open a web browser and search for the AP IP. This should open a page in which you can toggle the light of the in-built LED on and off.  
