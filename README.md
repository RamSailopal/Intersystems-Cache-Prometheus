# Intersystems-Cache-Prometheus


![Alt text](Intersystem%20Dashboard.PNG?raw=true "Intersystems Cache Dashboard")

The code in this repo allows for the integration of an Intersystems Cache environment with Prometheus/Grafana.

Typical system metrics are used in this particular dashboard, but this can easily be scaled to using bespoke application metrics also

Data is exposed from Cache to Prometheus via a cache server page


# Prerequisites

It is assumed that you have a functioning deployment of both Prometheus and Grafana with Prometheus able to "scape" metrics and Grafana able to see the scraped metric through the Prometheus plugin

