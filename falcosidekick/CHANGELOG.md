# Change Log

This file documents all notable changes to Falcosidekick Helm Chart. The release
numbering uses [semantic versioning](http://semver.org).

Before release 0.1.20, the helm chart can be found in `falcosidekick` [repository](https://github.com/falcosecurity/falcosidekick/tree/master/deploy/helm/falcosidekick). 

## 0.1.25

### Minor Changes

* Allow the configuration of the Pod securityContext, set default runAsUser and fsGroup values

## 0.1.24

### Minor Changes

* Remove duplicated `webhook` block in `values.yaml`

## 0.1.23

* fake release for triggering CI for auto-publishing

## 0.1.22

### Major Changes

* Add `imagePullSecrets`

## 0.1.21

### Minor Changes

* Fix `Azure Indentity` case sensitive value

## 0.1.20

### Major Changes

* New outputs can be set : `Azure Event Hubs`, `Discord`

### Minor Changes

* Fix wrong port name in output

## 0.1.17

### Major Changes

* New outputs can be set : `Mattermost`, `Rocketchat`

## 0.1.11

### Major Changes

* Add Pod Security Policy

## 0.1.11

### Minor Changes

* Fix wrong value reference for Elasticsearch output in deployment.yaml

## 0.1.10

### Major Changes

* New output can be set : `DogStatsD`
 
## 0.1.9

### Major Changes

* New output can be set : `StatsD`

## 0.1.7

### Major Changes

* New output can be set : `Opsgenie`

## 0.1.6

### Major Changes

* New output can be set : `NATS`

## 0.1.5

### Major Changes

* `Falcosidekick` and its chart are now part of `falcosecurity` organization

## 0.1.4

### Minor Changes

* Use more recent image with `Golang` 1.14

## 0.1.3

### Major Changes

* New output can be set : `Loki`

## 0.1.2

### Major Changes

* New output can be set : `SMTP`

## 0.1.1

### Major Changes

* New outputs can be set : `AWS Lambda`, `AWS SQS`, `Teams`

## 0.1.0

### Major Changes

* Initial release of Falcosidekick Helm Chart
