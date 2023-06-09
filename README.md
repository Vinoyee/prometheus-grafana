# prometheus-monitoring
Grafana
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/install-grafana.sh  -o install-grafana.sh

Prometheus
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/install-prometheus.sh -o install-prometheus.sh
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/prometheus.service -o prometheus.service
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/prometheus_serviceDiscovery.yml -o prometheus_serviceDiscovery.yml

Node
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/install-node-exporter.sh -o install-node-exporter.sh
curl -s --noproxy '*' https://bitbucket.org/terraform-code-vinoyee/test_repo/src/master/node-exporter.service -o node-exporter.service
