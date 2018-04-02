# esp32-homekit

# Build
```
$ git clone  https://github.com/younghyunjo/esp32-homekit.git
$ cd esp32-homekit
$ git submodule update --init --recursive
$ cd components/wolfssl
$ git checkout esp-idf
$ cd ../arduino
$ git checkout master
$ cd ../..
$ make
$ make flash
```

# WiFi Setting
1. Open main/main.c
2. Change EXAMPLE_WIFI_SSID, and EXAMPLE_WIFI_PASS
```
#define EXAMPLE_WIFI_SSID "unibj"  
#define EXAMPLE_WIFI_SSID "12345678"  
```

# Setup Code
"053-58-197"
