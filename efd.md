# Openshift Cluster information - On-Prem

Openshift supports both clusters hosted in Azure cloud and On-Prem(VmWare) platform

Here we have information for OPenshift onprem hosted cluster running on VMWaare infrastructure.

!!! tip "Visit [OCP Report](https://ocpreport-ocpreport-prod.apps.ocp-shared-v1-nonprod.volvocars.biz/ocpreport/ocr/index.html) to view complete list of clusters and other matrices"

## Openshif Cluster general information - Cluster hosted in VMWare (Vanilla Openshift)

| Cluster Name                  | Platform | Site/Region | Environments | Cluster Subnet     | LB Backend IPs   | Console URL                                                                 | API URL                                               | Vault Auth Backend     |
|-------------------------------|----------|-------------|--------------|--------------------|------------------|----------------------------------------------------------------------------|-------------------------------------------------------|-----------------------|
| `VCT-NON PROD_VANILLA (Torslanda)` | `Onprem` | `Torslanda` | `Non Prod`   | `10.120.44.0/23`   | `10.121.97.133`  | [Console](https://console-openshift-console.apps.iod-vct-qa.volvocars.net/) | `Api : https://api.iod-vct-qa.volvocars.net:6443`     | `iod-vct-qa-eu`       |
| `VCT-PROD_VANILLA (Torslanda)_`    | `Onprem` | `Torslanda` | `Prod`       | `10.120.44.0/23`   | `10.120.98.217`  | [Console](https://console-openshift-console.apps.iod-vct.volvocars.net/)    | `Api : https://api.iod-vct.volvocars.net:6443`        | `iod-vct-prod-eu`     |
| `VCCD-NON PROD _VANILLA (Chengdu)`| `Onprem` | `Chengdu`   | `Non Prod`   | `10.234.5.0/24`    | `10.239.0.26`    | [Console](https://console-openshift-console.apps.iod-vccd-qa.volvocars.net/) | `Api : https://api.iod-vccd-qa.volvocars.net:6443`    | `iod-vccd-qa-ch`      |
| `VCCD-PROD_VANILLA (Chengdu)`      | `Onprem` | `Chengdu`   | `Prod`       | `10.234.5.0/24`    | `10.239.0.28`    | [Console](https://console-openshift-console.apps.iod-vccd.volvocars.net/)   | `Api : https://api.iod-vccd.volvocars.net:6443`       | `NA`                  |
| `VCG-NON PROD_VANILLA (Ghent)`     | `Onprem` | `Ghent`     | `Non Prod`   | `10.249.1.64/26`   | `10.249.4.23`    | [Console](https://console-openshift-console.apps.iod-vcg-qa.volvocars.net/)  | `https://api.iod-vcg-qa.volvocars.net:6443`           | `iod-vcg-qa-eu`       |
| `VCG-PROD_VANILLA (Ghent)`         | `Onprem` | `Ghent`     | `Prod`       | `10.249.1.64/26`   | `10.249.4.25`    | [Console](https://console-openshift-console.apps.iod-vcg.volvocars.net/)     | `https://api.iod-vcg.volvocars.net:6443`              | `iod-vcg-prod-eu`     |
| `VCDQ-NON PROD_VANILLA (Daqing)`   | `Onprem` | `Daqing`    | `Non Prod`   | `10.240.66.64/26`  | `10.240.69.21`   | [Console](https://console-openshift-console.apps.iod-vcdq-qa.volvocars.net)  | `https://api.iod-vcdq-qa.volvocars.net:6443`          | `iod-vcdq-qa-ch`      |
| `VCDQ-PROD_VANILLA (Daqing)`       | `Onprem` | `Daqing`    | `Prod`       | `10.240.66.0/26`   | `10.240.69.23`   | [Console](https://console-openshift-console.apps.iod-vcdq.volvocars.net)     | `https://api.iod-vcdq.volvocars.net:6443`             | `NA`                  |
| `VCLQ-NON PROD_VANILLA (Luqiao)`   | `Onprem` | `Luqiao`    | `Non Prod`   | `10.235.2.0/24`    | `10.235.7.21`    | [Console](https://console-openshift-console.apps.iod-vclq-qa.volvocars.net/) | `https://api.iod-vclq-qa.volvocars.net:6443`          | `iod-vclq-qa-ch`      |
| `VCLQ-PROD_VANILLA (Luqiao)`       | `Onprem` | `Luqiao`    | `Prod`       | `10.235.2.0/24`    | `10.235.7.20`    | [Console](https://console-openshift-console.apps.iod-vclq.volvocars.net/)   | `https://api.iod-vclq.volvocars.net:6443`             | `NA`                  |
| `VCCH-NON PROD_VANILLA (Charleston)`| `Onprem`| `Charleston`| `Non Prod`   | `10.233.5.0/24`    | `10.233.2.23`    | [Console](https://console-openshift-console.apps.iod-vcch-qa.volvocars.net/) | `https://api.iod-vcch-qa.volvocars.net:6443`          | `iod-vcch-qa-us`      |
| `VCCH_PROD_VANILLA (Charleston)`   | `Onprem` | `Charleston`| `Prod`       | `10.233.5.0/24`    | `10.233.2.25`    | [Console](https://console-openshift-console.apps.iod-vcch.volvocars.net/)    | `https://api.iod-vcch.volvocars.net:6443`             | `iod-vcch-prod-eu`    |
| `VCBC- PROD`                      | `Onprem` | `Olofström` | `Prod`       | `10.250.131.0/24`  | `10.250.142.32`  | [Console](https://console-openshift-console.apps.iod-vcbc.volvocars.net/)   | `https://api.iod-vcbc.volvocars.net:6443`             | `iod-vcbc-prod-eu`    |
| `VCBC-NON PROD`                   | `Onprem` | `Olofström` | `Non Prod`   | `10.250.131.0/24`  | `10.250.142.28`  | [Console](https://console-openshift-console.apps.iod-vcbc-qa.volvocars.net/) | `https://api.iod-vcbc-qa.volvocars.net:6443`          | `iod-vcbc-qa-eu`      |
| `VCFL- PROD`                     | `Onprem` | `Floby`     | `Prod`       | `10.179.28.128/25` | `10.179.27.9`    | [Console](https://console-openshift-console.apps.iod-vcfl.volvocars.net/)   | `https://api.iod-vcfl.volvocars.net:6443`             | `iod-vcfl-prod-eu`    |
| `VCFL QA`                       | `Onprem` | `Floby`     | `Non Prod`   | `NA`               | `10.179.27.99`   | [Console](https://console-openshift-console.apps.iod-vcfl-qa.volvocars.net/) | `https://api.iod-vcfl-qa.volvocars.net:6443`          | `iod-vcfl-qa-eu`      |
| `VCFL PROD NEW`                 | `Onprem` | `Floby`     | `Prod`       | `NA`               | `10.179.27.102`  | [Console](https://console-openshift-console.apps.iod-vcfl-prod.volvocars.net)| `https://api.iod-vcfl-prod.volvocars.net:6443`        | `NA`                  |
| `VCFL Non-Prod`                | `Onprem` | `Floby`     | `Non Prod`   | `10.179.28.128/25` | `10.179.27.99`   | [Console](https://console-openshift-console.apps.iod-vcfl-nonprod.volvocars.net/) | `https://api.iod-vcfl-nonprod.volvocars.net:6443` | `iod-vcfl-nonprod-eu` |
| `VCT-Megacasting-PROD`         | `Onprem` | `Torslanda` | `Prod`       | `10.122.128.0/23`  | `10.254.229.42`  | [Console](https://console-openshift-console.apps.iod-vct-product.volvocars.net/) | `https://api.iod-vct-product.volvocars.net:6443` | `iod-vctp-prod-eu`     |
| `VCT-Megacasting-QA`           | `Onprem` | `Torslanda` | `Non Prod`   | `10.122.131.0/25`  | `10.254.229.12`  | [Console](https://console-openshift-console.apps.iod-vct-product-qa.volvocars.net/) | `https://api.iod-vct-product-qa.volvocars.net:6443` | `iod-vctp-qa-eu`       |
| `JIADING PROD CLUSTER`         | `Onprem` | `China`     | `Prod`       | `10.237.16.0/24`   | `10.231.4.29`    | [Console](https://console-openshift-console.apps.iod-jiading-prod.volvocars.net) | `"	https://api.iod-jiading-prod.volvocars.net:6443"`| `NA`                  |
| `JIADING NON-PROD CLUSTER`     | `Onprem` | `China`     | `Non Prod`   | `10.237.16.0/24`   | `10.231.4.27`    | [Console](https://console-openshift-console.apps.iod-jiading-qa.volvocars.net) | `https://api.iod-jiading-qa.volvocars.net:6443`      | `iod-jiading-qa-ch`    |
| `NEW SANDBOX CLUSTER`          | `Onprem` | `Sweden`    | `NA`         | `10.122.122.0/23`  | `10.121.97.157`  | [Console](https://console-openshift-console.apps.iod-sandbox.volvocars.net)  | `https://api.iod-sandbox.volvocars.net:6443`          | `iod-sandbox-eu`       |


!!! note

    - `Cluster Subnet` to be used for for firewall request as source subnet.
    - `LB Backend IPs` to be used for LB backend Pool IPs for custom URL's VIP, which is normally nodes where Openshift router PODs are targeted to run.
    - `API URL` is needed for accessing API cluster or for `oc` login.
    - `Vault Auth Backend` is used for onboarding namespace into `Central Vault`, for more details please rever [Namesoace Onboard](https://backstage.volvocars.biz/docs/default/component/ocp-admin-documentation/instructions/vault-namespace-onboard/)
