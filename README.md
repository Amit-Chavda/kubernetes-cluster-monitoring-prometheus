# kubernetes-cluster-monitoring-prometheus
monitoring kubernetes cluster using prometheus


## kubernetes prometheus setup
- Create kubentes namspace use following command:
 ``` 
 kubectl create namespace monitoring
 ```
- Download the source yaml configuration of prometheus kunbenetes components [here](https://github.com/bibinwilson/kubernetes-prometheus)
- Go through the steps given [here](https://devopscube.com/setup-kube-state-metrics/)
- In case you get error like "A namespace is stuck in the Terminating state" follow steps [here](https://www.ibm.com/docs/en/cloud-private/3.1.2?topic=console-namespace-is-stuck-in-terminating-state)

## Grafana Dashboards for kubernetes prometheus
- Try following Grafana IDs and import from Grafana:
  - 11663
  - 14518
  - 13838
  - 4018
  - 7550
  - 10670
