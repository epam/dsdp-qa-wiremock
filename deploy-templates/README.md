# wiremock

![Version: 1.9.1](https://img.shields.io/badge/Version-1.9.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 3.10.0](https://img.shields.io/badge/AppVersion-3.10.0-informational?style=flat-square)

A Helm chart for WireMock deployment on Kubernetes

**Homepage:** <https://wiremock.org>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| OSD-DDM |  |  |

## Source Code

* <https://github.com/wiremock/helm-charts>
* <https://github.com/wiremock/wiremock-docker>
* <https://github.com/wiremock/wiremock>

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| https://wiremock.github.io/helm-charts | wiremock | 1.9.1 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| wiremock.args[0] | string | `"--port=9021"` |  |
| wiremock.args[1] | string | `"--max-request-journal=1000"` |  |
| wiremock.args[2] | string | `"--global-response-templating"` |  |
| wiremock.args[3] | string | `"--root-dir=/home/wiremock/storage"` |  |