# Monitoring project

## tutorial
* guide: [https://www.circuits.dk/datalogger-example-using-sense-hat-influxdb-grafana/](https://www.circuits.dk/datalogger-example-using-sense-hat-influxdb-grafana/)
* dashboard base: [https://grafana.com/grafana/dashboards/4934](https://grafana.com/grafana/dashboards/4934)

## start app
`sudo python dataloggersensehat.py -db=logger_db -sn=sensehat -rn=111`

## Grafana
* start grafana service: `sudo service grafana-server start`

## InfluxDB
* start influxDB; `sudo service influxdb start`
