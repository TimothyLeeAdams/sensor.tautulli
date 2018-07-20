# sensor.tautulli

A platform which allows you to get information from Tautulli.
  
To get started put `/custom_components/sensor/tautulli.py` here:  
`<config directory>/custom_components/sensor/tautulli.py`  
  
**Example configuration.yaml:**

```yaml
sensor:
  platform: tautulli
  api_key: 24b6eac0a858748664878d146bf63623b4
  host: 192.168.1.14
  username: username
  keys:
    - title
    - media_type
```

**Configuration variables:**  

key | description  
:--- | :---  
**platform (Required)** | The sensor platform name.  
**api_key (Required)** | Your Tautulli api_key  
**host (Required)** | The IP adress of the server running Tautulli. 
**username (Required)** | The Plex user you want to monitor. 
**keys (Required)** | A list of [keys](keys.md) you want to monitor. 
**port (Optional)** | The port the Tautulli uses, defaults to `8181`  
  