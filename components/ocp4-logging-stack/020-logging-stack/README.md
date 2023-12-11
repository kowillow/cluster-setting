# Resources to be configured or created

- Cluster Logging instance
- Cluster Log Forwarder instance

## Folder tree

```bash
.
├── base
│   ├── kustomization.yaml
│   └── logging
│       └── clusterlogging.yaml
├── overlays
│   ├── dev
│   │   ├── forwarder
│   │   │   └── clusterlogforwarder.yaml
│   │   ├── kustomization.yaml
│   │   └── logging
│   │       └── clusterlogging.yaml
│   ├── lab
│   │   ├── forwarder
│   │   │   └── clusterlogforwarder.yaml
│   │   ├── kustomization.yaml
│   │   └── logging
│   │       └── clusterlogging.yaml
│   ├── pre
│   │   ├── forwarder
│   │   │   └── clusterlogforwarder.yaml
│   │   ├── kustomization.yaml
│   │   └── logging
│   │       └── clusterlogging.yaml
│   └── pro
│       ├── forwarder
│       │   └── clusterlogforwarder.yaml
│       ├── kustomization.yaml
│       └── logging
│           └── clusterlogging.yaml
└── README.md
```

# Official Documentation

[About the ClusterLogging custom resource](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-configuring-cr.html#cluster-logging-configuring-crd_cluster-logging-configuring-cr)<br>
[Configuring the log store](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-log-store.html)<br>
[Configuring logging subsystem storage](https://docs.openshift.com/container-platform/4.11/logging/config/cluster-logging-storage-considerations.html)
