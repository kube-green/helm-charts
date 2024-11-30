# kube-green Helm Chart

[![CNCF Landscape](https://img.shields.io/badge/CNCF%20Landscape-5699C6)](https://landscape.cncf.io/?item=orchestration-management--scheduling-orchestration--kube-green)

This chart is in beta and subject to change.

## Usage

Helm must be installed to use the chart. Please refer to [Helm](https://helm.sh/docs/intro/install/) for installation instructions.

Once Helm is installed, add the kube-green repository:

```sh
helm repo add kube-green https://kube-green.github.io/helm-charts/
```

and install it in the desired namespace (in the example below, the namespace is `kube-green`):

```sh
helm install kube-green kube-green/kube-green --namespace kube-green --create-namespace
```

Full documentation at: [https://kube-green.dev](https://kube-green.dev)

## Contributing

The source code of the Helm chart is available on [kube-green repo](https://github.com/kube-green/kube-green/tree/main/charts/kube-green).

We’re always excited to welcome new contributors to our project! Check out to the [CONTRIBUTING.md](https://github.com/kube-green/kube-green/blob/main/CONTRIBUTING.md) file for more information.
