# CDD Helm Charts
## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add cdd-helm-charts https://piyush5989.github.io/helm-chart-tests/

Install Simple chart without any service:

    helm install cdd-helm-charts/simple-chart

Install nginx-server:

    helm install cdd-helm-charts/nginx-server
