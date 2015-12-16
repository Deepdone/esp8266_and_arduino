#### button using esp8266/Arduino ####

- deepSleep(0)
- Using GPIO16 and NPN TR, reset is not permitted while device is running
- Use static ip for fast WIFI connection
- 22K R is changed to 330K

- WiFiClient::setLocalPortStart(micros() + vdd);
- wifi_set_phy_mode(PHY_MODE_11N);
- system_phy_set_rfoption(1);
- wifi_set_channel(channel);


![1](https://raw.githubusercontent.com/chaeplin/esp8266_and_arduino/master/_15-esp8266-dash-deepsleep-reset/pics/01.reset_switch_schem.png)

![2](https://raw.githubusercontent.com/chaeplin/esp8266_and_arduino/master/_15-esp8266-dash-deepsleep-reset/pics/connect.png)

![3](https://raw.githubusercontent.com/chaeplin/esp8266_and_arduino/master/_15-esp8266-dash-deepsleep-reset/pics/npntr.png)

![4](https://raw.githubusercontent.com/chaeplin/esp8266_and_arduino/master/_15-esp8266-dash-deepsleep-reset/pics/FullSizeRender%205.jpg)