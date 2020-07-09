# CDD Helm Charts
## Installing Charts from this Repository

### Direct Installation using helm install

    helm install --name simple-chart --repo https://piyush5989.github.io/helm-chart-tests/ simple-chart
    helm install --name nginx-server --repo https://piyush5989.github.io/helm-chart-tests/ nginx-server

### Add Repo locally and install

Add the Repository to Helm:

    helm repo add cdd-helm-charts https://piyush5989.github.io/helm-chart-tests/

Install Simple chart without any service:

    helm install cdd-helm-charts/simple-chart

Install nginx-server:

    helm install cdd-helm-charts/nginx-server
