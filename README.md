# EasySSDP
Easy SSDP setup function for ESP8266 on Arduino. Makes Devices visible on Windows Network

![](https://i.imgur.com/ygILC2n.png)

# Usage
Simply call the `begin` function in `setup` and pass your `ESP8266WebServer` object as an argument.

```cpp
  //default device name "ESP8266
  EasySSDP::begin(server);
  
  //or optional device name
  EasySSDP::begin(server, "my esp8266 device name");
  ```

