# lcu-api
League Client REST API / Swagger docs - v11.18

### 🧨 How to use?

- Turn your Chromium browser into insecure mode, or just unblock CORS with [this extension](https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino)
- Visit Swagger UI live demo here: https://petstore.swagger.io/
- Copy raw link of [swagger.json](https://github.com/nomi-san/lcu-api/raw/main/swagger.json) or [openapi.json](https://github.com/nomi-san/lcu-api/raw/main/openapi.json)
- Paste it to the URL bar in Swagger UI, then click Explore

### 🍳 How to retrieve from League Client?

- Turn off all running clients
- Open **sysem.yaml** in LeagueClient folder and add `enable_swagger: true` to the end
- Run client
- Get port and password in **lockfile**
```
https://127.0.0.1:PORT/swagger/v2/swagger.json
https://127.0.0.1:PORT/swagger/v3/openapi.json
```
