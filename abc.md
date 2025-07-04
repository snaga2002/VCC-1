
# Cluster information - Hosted on Azure

Openshift supports both clusters hosted in Azure cloud and On-Prem(VmWare) platform

Dedicated clusters are also set up forapplication like `PIE`, `Car services`, `Maximo` and `CIL`

!!! tip "Visit [OCP Report](https://ocpreport-ocpreport-prod.apps.ocp-shared-v1-nonprod.volvocars.biz/ocpreport/ocr/index.html) to view complete list of clusters and other matrices"

## OpenShift Cluster General Information - Cluster hosted in Azure (Vanilla OpenShift and ARO)

| Cluster Name                  | Platform     | Site/Region | Environments | Compute Subnet       | LB Backend IPs   | Console URL                                                                                     | API URL                                                     | Vault Auth Backend        |
|------------------------------|--------------|-------------|--------------|-----------------------|------------------|--------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------|
| `sandbox-net`                | `Azure`      | `WEU`       | `NA`         | `NA`                  | `10.41.159.42`   | [`Console`](https://console.openshift-console.apps.sandbox-net.sandbox.volvocars.net)           | `https://api.sandbox-net.sandbox.volvocars.net:6443`        | `NA`                      |
| `pie-nonprod`                | `Azure`      | `WEU`       | `Non Prod`   | `10.48.66.160/27`     | `10.48.66.172`   | [`Console`](https://console-openshift-console.apps.pie-nonprod.volvocars.biz/)                  | `https://api.pie-nonprod.volvocars.biz:6443`                | `pie-nonprod-weu`         |
| `pie-prod`                   | `Azure`      | `WEU`       | `Prod`       | `10.48.67.32/27`      | `10.48.67.44`    | [`Console`](https://console-openshift-console.apps.pie-prod.volvocars.biz)                     | `https://api.pie-prod.volvocars.biz:6443`                   | `pie-prod-weu`            |
| `ocp-shared-v1-nonprod`      | `Azure`      | `WEU`       | `Non Prod`   | `10.48.129.128/26`    | `10.48.129.135`  | [`Console`](https://console-openshift-console.apps.ocp-shared-v1-nonprod.volvocars.biz)        | `https://api.ocp-shared-v1-nonprod.volvocars.biz:6443`      | `shared-v1-np-weu`        |
| `ocp-shared-v1-prod`         | `Azure`      | `WEU`       | `Prod`       | `10.48.128.128/26`    | `10.48.128.141`  | [`Console`](https://console-openshift-console.apps.ocp-shared-v1-prod.volvocars.biz/)          | `https://api.ocp-shared-v1-prod.volvocars.biz:6443`         | `shared-v1-prod-weu`      |
| `carservice-nonprod`         | `Azure`      | `WEU`       | `Non Prod`   | `10.49.202.192/26`    | `10.49.202.205`  | [`Console`](https://console-openshift-console.apps.carservice-nonprod.volvocars.biz/)          | `https://api.carservice-nonprod.volvocars.biz:6443`         | `carservice-np-weu`       |
| `carservice-prod`            | `Azure`      | `WEU`       | `Prod`       | `10.49.201.64/26`     | `10.49.201.77`   | [`Console`](https://console-openshift-console.apps.carservice-prod.volvocars.biz/)             | `https://api.carservice-prod.volvocars.biz:6443`            | `carservice-prod-weu`     |
| `shared-azureocp-nonprod`    | `Azure-ARO`  | `WEU`       | `Non Prod`   | `10.50.114.64/26`     | `10.50.114.126`  | [`Console`](https://console-openshift-console.apps.shared-azureocp-nonprod.volvocars.biz/)     | `https://api.shared-azureocp-nonprod.volvocars.biz:6443`    | `shared-aro-np-weu`       |
| `shared-azureocp-prod`       | `Azure-ARO`  | `WEU`       | `Prod`       | `10.50.113.64/26`     | `10.50.113.126`  | [`Console`](https://console-openshift-console.apps.shared-azureocp-prod.volvocars.biz/)        | `https://api.shared-azureocp-prod.volvocars.biz:6443`       | `shared-aro-pr-weu`       |
| `ocplus-prod.ocp-mgmt`       | `Azure`      | `WEU`       | `Prod`       | `10.50.100.64/26`     | `10.50.100.76`   | [`Console`](https://console-openshift-console.apps.ocplus-prod.ocp-mgmt.volvocars.net/)        | `https://api.ocplus-prod.ocp-mgmt.volvocars.net:6443`       | `ocplus-prod-weu`         |
| `mq-azureocp-nonprod`        | `Azure-ARO`  | `WEU`       | `Non Prod`   | `10.50.144.64/26`     | `10.50.145.126`  | [`Console`](https://console-openshift-console.apps.mq-azureocp-nonprod.volvocars.net/)         | `https://api.mq-azureocp-nonprod.volvocars.net`             | `mq-aro-np-weu`           |
| `mq-azureocp-prod`           | `Azure-ARO`  | `WEU`       | `Prod`       | `10.50.145.64/26`     | `10.50.144.126`  | [`Console`](https://console-openshift-console.apps.mq-azureocp-prod.volvocars.net/)            | `https://api.mq-azureocp-prod.volvocars.net`                | `mq-aro-prod-weu`         |
| `maximo-nonprod`             | `Azure`      | `WEU`       | `Non Prod`   | `10.50.176.0/24`      | `10.50.176.48`   | [`Console`](https://console-openshift-console.apps.maximo-nonprod.volvocars.net)               | `https://api.maximo-nonprod.volvocars.net:6443`             | `NA`                      |
| `maximo-prod`                | `Azure`      | `WEU`       | `Prod`       | `10.50.175.64/27`     | `10.50.175.76`   | [`Console`](https://console-openshift-console.apps.maximo-prod.volvocars.net/)                 | `https://api.maximo-prod.volvocars.net:6443`                | `NA`                      |
| `maximo-training`            | `Azure`      | `WEU`       | `Non Prod`   | `10.50.176.96/27`     | `10.50.176.108`  | [`Console`](https://console-openshift-console.apps.maximo-training.volvocars.net/)             | `https://api.maximo-training.volvocars.net:6443`            | `NA`                      |
| `maximo-qa`                  | `Azure`      | `WEU`       | `Non Prod`   | `10.50.176.64/27`     | `10.50.176.76`   | [`Console`](https://console-openshift-console.apps.maximo-qa.volvocars.net/)                   | `https://api.maximo-qa.volvocars.net:6443`                  | `NA`                      |
| `maximo-dev`                 | `Azure`      | `WEU`       | `Non Prod`   | `10.50.176.128/27`    | `10.50.176.137`  | [`Console`](https://console-openshift-console.apps.maximo-dev.volvocars.net)                   | `https://api.maximo-dev.volvocars.net:6443`                 | `NA`                      |
| `cil-azureocp-nonprod`       | `Azure-ARO`  | `WEU`       | `Non Prod`   | `10.55.27.64/26`      | `10.55.27.126`   | [`Console`](https://console-openshift-console.apps.cil-azureocp-nonprod.volvocars.biz/)        | `https://api.cil-azureocp-nonprod.volvocars.biz:6443`       | `cil-aro-np-weu`          |
| `cil-azureocp-prod`          | `Azure-ARO`  | `WEU`       | `Prod`       | `10.46.41.64/26`      | `10.46.41.126`   | [`Console`](https://console-openshift-console.apps.cil-azureocp-prod.volvocars.biz/)           | `https://api.cil-azureocp-prod.volvocars.biz:6443`          | `cil-aro-prod-weu`        |
| `observability-nonprod`      | `Azure`      | `WEU`       | `Non Prod`   | `10.46.21.64/26`      | `10.46.21.126`   | [`Console`](https://console-openshift-console.apps.observability-nonprod.volvocars.biz)        | `https://api.observability-nonprod.volvocars.biz:6443`      | `observability-nonprod-weu` |
| `observability-prod`         | `Azure`      | `WEU`       | `Prod`       | `10.46.24.64/26`      | `10.46.24.126`   | [`Console`](https://console-openshift-console.apps.observability-prod.volvocars.biz/)          | `https://api.observability-prod.volvocars.biz:6443`         | `NA`                      |
| `turbonomic-prod`            | `Azure`      | `WEU`       | `Prod`       | `10.46.32.64/26`      | `10.46.32.126`   | [`Console`](https://console-openshift-console.apps.turbonomic-prod.volvocars.biz/)             | `https://api.turbonomic-prod.volvocars.biz:6443`            | `NA`                      |


!!! note

    - `Cpmpute Subnet` to be used for for firewall request as source subnet.
    - `Ingress IP` to be used for LB backend Pool IPs for custom URL's VIP, which is the default IP for all Ingress to the cluster.
    - `API URL` is needed for accessing API cluster or for `oc` login.
    - `Vault Auth Backend` is used for onboarding namespace into `Central Vault`, for more details please rever [Namesoace Onboard](https://backstage.volvocars.biz/docs/default/component/ocp-admin-documentation/instructions/vault-namespace-onboard/)
