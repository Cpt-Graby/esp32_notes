
# ESP32 Notes

Ever heard of Arduino? Yeah, if you like that, you should maybe take a look at the ESP32.  
Well, at least I wanted to write a few notes on what I discovered about the ESP32.  

## Where to start

I just bought a few ESP32s on AliExpress for a few bucks.  
There seem to be a lot of different models — I got an "ESP32-WROOM-32".  
First things first: how do you code on it? Well, i just follow these instructions:  
`https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/index.html`  
then you can use some of those usefull cmd:  
```bash
idf.py build
idf.py -p PORT flash
idf.py -p <PORT> monitor
idf.py -p PORT erase-flash
```

## 
