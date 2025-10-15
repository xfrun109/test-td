# Grafana

## Description
This document outlines the integration of [Grafana](https://grafana.com/) into our Depo application by the enabling feature teams to display dashboards and alerts.

### About Grafana
For those of us who are less technical, Grafana is an open-source observability platform for monitoring, visualization, and analytics — primarily used to
explore, query, and display metrics, logs, and traces from various data sources in real time.

#### 💻 Typical Use Cases

- **System monitoring**: visualize server metrics (CPU, memory, network, etc.) from Prometheus or InfluxDB.
- **Application performance monitoring (APM)**: visualize logs and traces to debug production issues.
- **Business intelligence**: show KPIs, sales, or performance metrics from SQL databases.
- **IoT and automations**: display real-time sensor data.

## Features Added

- [Added quick link](https://depo-portal-ui-tooling.tst.tog.azure.dsb.dk) to the toolkit items to easily find DBS's Grafana resources
- Provided a sample dashboard for displaying [`Delivery Station Team`(DST) configured dashboards](https://depo-portal-ui-tooling.tst.tog.azure.dsb.dk/catalog/default/component/frantz-test-md)
The current list of dashboards from DST team as provided by Salman can be found [here](https://grafana.azure.dsb.dk/dashboards/f/bey91x9bolb7ka/?orgId=1)
- Updated [documentation](https://github.com/DanskeStatsbaner/depo-dev-portal/blob/main/docs/plugins.md#grafana) for both internal usage and feature team integrations with full working examples
