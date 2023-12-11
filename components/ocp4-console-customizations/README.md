# Resources to be configured or created

- image.config

## Folder tree

```bash
.
├── base
│   ├── ingress.config
│   │   └── cluster.yaml
│   └── kustomization.yaml
├── overlays
│   ├── dev
│   │   ├── ingress.config
│   │   │   └── cluster.yaml
│   │   ├── kustomization.yaml
│   │   ├── notification
│   │   │   └── topbanner.yaml
│   │   └── operator
│   │       └── console.operator.yaml
│   ├── lab
│   │   ├── ingress.config
│   │   │   └── cluster.yaml
│   │   ├── kustomization.yaml
│   │   ├── notification
│   │   │   └── topbanner.yaml
│   │   └── operator
│   │       └── console.operator.yaml
│   ├── pre
│   │   ├── ingress.config
│   │   │   └── cluster.yaml
│   │   ├── kustomization.yaml
│   │   ├── notification
│   │   │   └── topbanner.yaml
│   │   └── operator
│   │       └── console.operator.yaml
│   └── pro
│       ├── ingress.config
│       │   └── cluster.yaml
│       ├── kustomization.yaml
│       ├── notification
│       │   └── topbanner.yaml
│       └── operator
│           └── console.operator.yaml
└── README.md
```

# Official Documentation

[Customizing the web console in OpenShift Container Platform](https://docs.openshift.com/container-platform/4.11/web_console/customizing-the-web-console.html)<br>
[Customizing the console route](https://docs.openshift.com/container-platform/4.11/web_console/customizing-the-web-console.html#customizing-the-console-route_customizing-web-console)<br>
[Adding a custom logo and product name](https://docs.openshift.com/container-platform/4.11/web_console/customizing-the-web-console.html#adding-a-custom-logo_customizing-web-console)<br>
[Creating custom notification banners](https://docs.openshift.com/container-platform/4.11/web_console/customizing-the-web-console.html#creating-custom-notification-banners_customizing-web-console)
