# Prometheus Switchbot Exporter ![Image Version] ![Image Size] [![Release badge]][Release status]

A Prometheus exporter for [SwitchBot Meter] devices.

## Usage

The simplest way to deploy this exporter is on Kubernetes, using the Helm chart
provided.

```sh
$ helm repo add prometheus-switchbot-exporter https://louisblin.github.io/prometheus-switchbot-exporter
$ helm install switchbot-exporter prometheus-switchbot-exporter/prometheus-switchbot-exporter
```

[Image Size]: https://img.shields.io/docker/image-size/louisleblin/prometheus-switchbot-exporter?sort=date
[Image Version]: https://img.shields.io/docker/v/louisleblin/prometheus-switchbot-exporter?sort=date
[Release badge]: https://github.com/louisblin/prometheus-switchbot-exporter/actions/workflows/release.yaml/badge.svg
[Release status]: https://github.com/louisblin/prometheus-switchbot-exporter/actions/workflows/release.yaml
[SwitchBot Meter]: https://www.switch-bot.com/products/switchbot-meter