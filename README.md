# iota-prom-exporter
Prometheus Exporter for IOTA metrics

Works with Prometheus and (optionally) Grafana to create service metrics and a dashboard (Grafana) for analysis of the metrics. 

Currently includes metrics from the api like `getNodeInfo()` and `getNeighbors()`

Also includes market status using bitfinex's api for IOTUSD, IOTBTC and IOTETH (price and volume)

Just clone the repo then from the root run `npm install` then `node app.js`