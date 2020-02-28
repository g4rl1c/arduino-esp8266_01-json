# Arduino ESP8266 01 JSON

JSON files on a esp8266 01 1M using arduino framework, PlatformIO on VS Code

## Uploading to File System

To upload JSON files into the File System, it needs to be created a data (data is the default dir_path, if you need another one, you will need to set it up at platformio.ini).

Use

```
pio run -t uploadfs
```

## Functions

> **serializeMyJson(Sring ssid, String pass)**

This function serialize a **String** from the 2 parameters given

- **ssid**: as the SSID
- **pass**: as the SSID Password

> **deserializeMyJson(String jsonSring)**

This function deserialize a given **JSON String**

#### Note

This code was built for references only. It can be improved, and if anyone wants to help, let me know
