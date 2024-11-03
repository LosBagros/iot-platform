# IoT Platform

- MQTT
- Telegraf
- TimescaleDB
- Grafana


## Create user

```bash
docker run -it --rm eclipse-mosquitto -v ./mosquitto/:/mosquitto/  mosquitto_passwd -c /mosquitto/config/passwords <username>
```

## Edit `.env`

```bash
mv .env.example .env
vi .env
```

## Deploy

```bash
docker compose up -d
```
