nexus-app-chart
This Helm chart deploys the Nexus application on a EKS Cluster
Prerequisites:

EKS Cluster (AWS) : must be set up first
Helm must be created with the "helm create repo"


Installing the Chart
To install the chart with the release name : nexus-app-release


helm install nexus-app-release  ./nexus-app-chart




Upgrading your Chart
To upgrade the chart with the release name : nexus-app-release


helm upgrade nexus-app-release  ./nexus-app-chart




Installing the Chart with values.yaml
To install the chart with the release name : nexus-app-release


helm install nexus-app-release  ./nexus-app-chart --Values ./nexus-app-chart/values.yaml




Uninstalling the Chart
To uninstall the nexus-app -release deployment:


helm uninstall nexus-app-release  ./nexus-app-chart
