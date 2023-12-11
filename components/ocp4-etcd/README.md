# Resources to be configured or created

- Configure the APIServer resource to enable the encryption

## Folder tree

```bash
.
├── base
│   ├── apiserver
│   │   └── apiserver.yaml
│   └── kustomization.yaml
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

[Enabling etcd encryption](https://docs.openshift.com/container-platform/4.11/security/encrypting-etcd.html#enabling-etcd-encryption_encrypting-etcd)
