# kube-prometheus-stack
## 参考命令和配置
参考文档：https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack
参考命令
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```
修改Values.yaml参考prometheus-self/kube-prometheus-stack/prometheus.yaml
```
helm install -f prometheus.yaml prometheus-stack prometheus-community/prometheus
```