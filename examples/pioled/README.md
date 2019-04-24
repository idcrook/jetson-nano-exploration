# Using PiOLED from (CircuitPython) Python code


[https://blog.adafruit.com/2019/03/18/adafruit-blinka-support-for-the-nvidia-jetson-series-nvidia-gtc19-nvidiaembedded/](https://blog.adafruit.com/2019/03/18/adafruit-blinka-support-for-the-nvidia-jetson-series-nvidia-gtc19-nvidiaembedded/)


## Install Adafruit Blinka - CircuitPython hardware API and libraries

- [https://github.com/adafruit/Adafruit\_Blinka](https://github.com/adafruit/Adafruit_Blinka)
 - [https://github.com/adafruit/Adafruit\_CircuitPython\_Bundle/blob/master/circuitpython\_library\_list.md](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/master/circuitpython_library_list.md)


```bash
sudo apt update && sudo apt install python3-pip python3-setuptools
sudo pip3 install adafruit-blinka
```

Docs: [https://learn.adafruit.com/circuitpython-on-raspberrypi-linux](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux)

## display example PiOLED

"updated" example: [https://learn.adafruit.com/adafruit-pioled-128x32-mini-oled-for-raspberry-pi](https://learn.adafruit.com/adafruit-pioled-128x32-mini-oled-for-raspberry-pi)

### Install required libraries

```bash
sudo pip3 install adafruit-circuitpython-ssd1306
sudo apt-get install python3-pil
```


## code

 - [hello_world.py](hello_world.py): Light up well-known pixels
```
sudo python3 hello_world.py
```

- [stats.py](stats.py): Display system stats on PiOLED
  - modified example to also display (to stdout) addresses of I2C devices detected

```
sudo python3 stats.py
```
