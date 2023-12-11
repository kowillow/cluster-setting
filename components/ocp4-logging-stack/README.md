# NOTE

To configure the Logging Stack, the required operators needs to be deployed at the cluster.

First, you need to apply the ElasticSearch and Logging operators resources.

The installPlan approval it's configured to Manual approvation, you need first to approve the Operators deploy and after apply the ClusterLogging customization.

## Folder tree

```bash
.
├── 010-logging-operator
│   ├── base
│   │   ├── kustomization.yaml
│   │   ├── namespace
│   │   │   ├── elasticsearch.yaml
│   │   │   └── logging.yaml
│   │   ├── operatorgroup
│   │   │   ├── elasticsearch.yaml
│   │   │   └── logging.yaml
│   │   └── subscription
│   │       ├── elasticsearch.yaml
│   │       └── logging.yaml
│   ├── overlays
│   │   ├── dev
│   │   │   └── kustomization.yaml
│   │   ├── lab
│   │   │   └── kustomization.yaml
│   │   ├── pre
│   │   │   └── kustomization.yaml
│   │   └── pro
│   │       └── kustomization.yaml
│   └── README.md
├── 020-logging-stack
│   ├── base
│   │   ├── kustomization.yaml
│   │   └── logging
│   │       └── clusterlogging.yaml
│   ├── overlays
│   │   ├── dev
│   │   │   ├── forwarder
│   │   │   │   └── clusterlogforwarder.yaml
│   │   │   ├── kustomization.yaml
│   │   │   └── logging
│   │   │       └── clusterlogging.yaml
│   │   ├── lab
│   │   │   ├── forwarder
│   │   │   │   └── clusterlogforwarder.yaml
│   │   │   ├── kustomization.yaml
│   │   │   └── logging
│   │   │       └── clusterlogging.yaml
│   │   ├── pre
│   │   │   ├── forwarder
│   │   │   │   └── clusterlogforwarder.yaml
│   │   │   ├── kustomization.yaml
│   │   │   └── logging
│   │   │       └── clusterlogging.yaml
│   │   └── pro
│   │       ├── forwarder
│   │       │   └── clusterlogforwarder.yaml
│   │       ├── kustomization.yaml
│   │       └── logging
│   │           └── clusterlogging.yaml
│   └── README.md
└── README.md
```

# Official Documentation

[About the ClusterLogging custom resource](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-configuring-cr.html#cluster-logging-configuring-crd_cluster-logging-configuring-cr)<br>
[Configuring the log store](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-log-store.html)<br>
[Configuring logging subsystem storage](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-storage-considerations.html)
