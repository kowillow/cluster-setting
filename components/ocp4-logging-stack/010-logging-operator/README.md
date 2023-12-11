# Resources to be configured or created

- Required namespaces
- ElasticSearch OperatorGroup and Subscription
- Openshift Logging OperatorGroup and Subscription

NOTE: The applied configuration have the installPlan approval policy as manual, after the apply of this resources, you need to review the generated installPlan and approve it.

## Folder tree

```bash
.
├── base
│   ├── kustomization.yaml
│   ├── namespace
│   │   ├── elasticsearch.yaml
│   │   └── logging.yaml
│   ├── operatorgroup
│   │   ├── elasticsearch.yaml
│   │   └── logging.yaml
│   └── subscription
│       ├── elasticsearch.yaml
│       └── logging.yaml
├── overlays
│   ├── dev
│   │   └── kustomization.yaml
│   ├── lab
│   │   └── kustomization.yaml
│   ├── pre
│   │   └── kustomization.yaml
│   └── pro
│       └── kustomization.yaml
└── README.md
```

# Official Documentation

[Installing the logging subsystem for Red Hat OpenShift using the CLI](https://docs.openshift.com/container-platform/4.11/logging/cluster-logging-deploying.html#cluster-logging-deploy-cli_cluster-logging-deploying)
