# InfluxDBv2 Telegraf Docker

 Run InfluxDB 2.0 and Telegraf in containers, with http input plugin configured.

## How to Run

1. `docker-compose up`
2. access influxdb ui on `localhost:8086` myusername/passwordpassword/password

 Credit: Inspired from [this](https://github.com/InfluxCommunity/InfluxDBv2_Telegraf_Docker) by [Anaisdg](https://github.com/Anaisdg)

Important links:

- [To read more about http plugin](https://github.com/influxdata/telegraf/blob/release-1.22/plugins/inputs/http/README.md)
- [To read more about http json parser](https://github.com/influxdata/telegraf/tree/release-1.22/plugins/parsers/json_v2)
