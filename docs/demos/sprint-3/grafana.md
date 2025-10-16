# Grafana integration for DSB Systems & Components

## 📖 Description
This document outlines the integration of <a href"https://grafana.com" target=_blank>Grafana</a> into our Depo application by the enabling feature teams to display dashboards and alerts.

### About Grafana
For those of us who are less technical, Grafana is an open-source observability platform for monitoring, visualization, and analytics — primarily used to
explore, query, and display metrics, logs, and traces from various data sources in real time.

#### 💻 Typical Use Cases

- **System monitoring**: visualize server metrics (CPU, memory, network, etc.) from Prometheus or InfluxDB.
- **Application performance monitoring (APM)**: visualize logs and traces to debug production issues.
- **Business intelligence**: show KPIs, sales, or performance metrics from SQL databases.
- **IoT and automations**: display real-time sensor data.

## 🎯 Features Added

- <a href"https://depo-portal-ui-tooling.tst.tog.azure.dsb.dk" target=_blank>Added quick link</a> to the toolkit items to easily find DBS's Grafana resources
- Provided a sample dashboard for displaying [`Delivery Station Team`(DST) configured dashboards](https://depo-portal-ui-tooling.tst.tog.azure.dsb.dk/catalog/default/component/frantz-test-md)
The current list of dashboards from DST team as provided by Salman can be found [here](https://grafana.azure.dsb.dk/dashboards/f/bey91x9bolb7ka/?orgId=1)
- Updated [documentation](https://github.com/DanskeStatsbaner/depo-dev-portal/blob/main/docs/plugins.md#grafana) for both internal usage and feature team integrations with full working examples

## 🎉 Ideas for Future Improvements
- Customize the Grafana plugin to fit our needs (title setup from the remote repository, display other useful information (eg: Description, tags, last modified), etc)
- Extend Grafana beyond componets and display those dashboards also for API's for example
- Auto discover Grafana for each System & Component provided withot
- Add embedding support for dashboards and alerts

## Q & A
![Q&A](assets/brace-yourself.png)
