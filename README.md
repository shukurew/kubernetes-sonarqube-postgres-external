After digging 8 hours I deployed Sonarqube with external database via [Helm chart][1] 

here is `values.yaml` edit last line with your PostgresQL credentials

`helm repo add bitnami https://charts.bitnami.com/bitnami`

`helm install sonarqube -f values.yaml  oci://registry-1.docker.io/bitnamicharts/sonarqube -n sonarqube`


  [1]: https://artifacthub.io/packages/helm/bitnami/sonarqube
