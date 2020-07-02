# Helm Charts

This repository contains some Helm Charts.

To use the charts, add the `niclic` repo to your list of Helm repositories.

```sh
helm repo add niclic https://niclic.github.com/helm-charts

```

Later, to get new versions of charts, update your list of repositories.

```sh
helm repo update

```

Review the list of available charts.

```sh
helm search repo niclic

```


## Charts

* [prometheus-statsd-exporter](https://github.com/niclic/helm-charts/tree/master/prometheus-statsd-exporter)

This chart is an updated version of the original unmerged PR in the [Helm Repo](https://github.com/helm/charts/pull/7506).

To install this chart, use something like this.

```sh
# install prometheus-statsd-exporter
helm install prometheus-statsd-exporter niclic/prometheus-statsd-exporter

```


## Contributing

Contributions are welcome via GitHub pull requests.
