+++
title = "Connect"
date = 2018-12-09T17:04:27-05:00
weight = 300
chapter = true
draft = true
+++

## Connecting to your GKE Cluster

### Prerequisites 

[Follow the Requirements](/intro-k8/introduction/requirements)


### Retrieve Cluster Credentials (make sure there's no conflict with a pre-existing KUBECONFIG var) ###
```
gcloud container clusters get-credentials <cluster-name> --region <region>
```

### Confirm Cluster Connectivity
```
kubectl cluster-info
```
