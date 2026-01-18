# dra-driver-topology

This repository contains a reference resource driver implemented as a Kubernetes controller to expose topological node information against Dynamic Resource Allocation (DRA) APIs.

# Development

You can run the controller locally with `make run`. The controller will read
your `$KUBECONFIG` environment, or you may specify one of the standard
kubeconfig flags to an `ARGS` environment variable to give it access to a
control plane. 

For example:

```
make run ARGS="--kube-server=https://127.0.0.1:46777 --v 5"
```

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](http://kubernetes.io/community/).

You can reach the maintainers of this project at:

- [Slack channel](https://kubernetes.slack.com/messages/sig-scheduling)
- [Mailing List](https://groups.google.com/a/kubernetes.io/g/sig-scheduling)

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](code-of-conduct.md).
