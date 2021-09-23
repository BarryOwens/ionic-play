This part of the code is for starting to configure how datadog might look in an ArgoCD integration with CHIPS's ArgoCD

The file datadog.yaml would be added here:
https://bitbucket.org/oliverwymantechssg/chips-helm-charts/src/master/charts/cluster-applications/latest/

values.yaml would be merged with the values.yaml in that repo.

Deploying would be something like:
Add the cluster to ArgoCD Whitelisted clusters 
Manually add the secret into the generated namespace 

