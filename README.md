# k8s-images

## query image versions
curl https://gcr.io/v2/google_containers/heapster-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/addon-resizer/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/heapster-grafana-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/heapster-influxdb-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kubernetes-dashboard-init-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/defaultbackend/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kubernetes-kafka/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kubernetes-zookeeper/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/zookeeper-install/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/zookeeper-install-3.5.0-alpha/tags/list | python -m json.tool

curl https://gcr.io/v2/google_containers/k8s-dns-sidecar-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/k8s-dns-kube-dns-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/k8s-dns-dnsmasq-nanny-amd64/tags/list | python -m json.tool

curl https://gcr.io/v2/google_containers/pause-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/etcd-amd64/tags/list | python -m json.tool

curl https://gcr.io/v2/google_containers/kube-apiserver-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kube-controller-manager-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kube-proxy-amd64/tags/list | python -m json.tool
curl https://gcr.io/v2/google_containers/kube-scheduler-amd64/tags/list | python -m json.tool

curl https://gcr.io/v2/google_containers/kubernetes-dashboard-amd64/tags/list | python -m json.tool
