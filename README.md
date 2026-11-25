# Smart Home & Security
1. Flash esp32_firmware/smart_home.ino (set Wi-Fi name/password). Open Serial Monitor, note the IP.
2. Open this folder in Android Studio, let Gradle sync, run on your phone (same Wi-Fi).
3. Tap +, enter the IP. Toggle outputs, arm/disarm, see sensors, get alarm notifications.

Any other board (ESP8266, Pico W...) works if it serves: GET /api/state, POST /api/output?id=&on=, POST /api/arm?on=
