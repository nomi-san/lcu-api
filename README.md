# lcu-api
League Client REST API / Swagger docs - v12.3

### 🧨 How to use?

1. Turn your Chromium browser into insecure mode, or just unblock CORS with [this extension](https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino)
2. Visit Swagger UI live demo here: https://petstore.swagger.io/
3. Copy raw link of [swagger.json](https://github.com/nomi-san/lcu-api/raw/main/swagger.json) or [openapi.json](https://github.com/nomi-san/lcu-api/raw/main/openapi.json)
4. Paste it to the URL bar in Swagger UI, then click Explore

### 🍳 How to retrieve from League Client?

1. Turn off all running clients
2. Open **sysem.yaml** in LeagueClient folder and add this line to the end
```yaml
enable_swagger: true
```
3. Launch LeagueClient
4. Get port and password in **lockfile**
```
LeagueClient:%PID:%PORT:%PASS:%PROTOCOL
```
6. Access these URLs
```
https://127.0.0.1:%PORT/swagger/v2/swagger.json
https://127.0.0.1:%PORT/swagger/v3/openapi.json
```
- Replace `%PORT` with your port
- Login prompt appears, enter `riot` as username and your password
