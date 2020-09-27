# Kubernetes Helm Libraries by Blue Spire
Both Open Source and proprietary Projects, customized to provide easy to use tools making it an enterprise class products

## TL;DR

```bash
$ helm repo add bluespireinc https://github.com/bluespireinc/charts
$ helm search repo bluespireinc
$ helm install my-release bluespireinc/<chart>
```
### Install Helm

Helm is a tool for managing Kubernetes charts. Charts are packages of pre-configured Kubernetes resources.

To install Helm, refer to the [Helm install guide](https://github.com/helm/helm#install) and ensure that the `helm` binary is in the `PATH` of your shell.

### Add Repo

The following command allows you to download and install all the charts from this repository:

```bash
$ helm repo add bluespireinc https://github.com/bluespireinc/charts
```

### License

Copyright (c) 2020 Blue Spire, inc

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
