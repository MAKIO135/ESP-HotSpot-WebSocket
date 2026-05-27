# ESP HotSpot and WebSocket Server + ESP and JS Clients

Working on places with often limited WiFi, the idea behind this project is to have an ESP board like the Feather Huzzah(ESP 8266) or Huzzah32 to create a Wifi hotspot and a WebSocket server that broadcasts all the messages it receives. 

⚠️ Chrome now treats `localhost` as an insecure origin unless using a HTTPS certificate and will block usage of websockets. You can still modify this behavior by activating this chrome flag:  
[chrome://flags/#unsafely-treat-insecure-origin-as-secure](chrome://flags/#unsafely-treat-insecure-origin-as-secure)
