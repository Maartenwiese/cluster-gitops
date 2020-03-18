# Managed Cloud Cluster Ops

This is an example repository, used for managing on-prem clusters with GitOps.

- [namespaces](./namespaces): creates three namespaces for the cluster: `itops`, `team-a`, and `team-b`, these namespaces are managed by the I
- [cluster-apps](./cluster-apps): contains an application deployed by an IT operator, e.g. common monitoring or logging agent
- [team-a](./team-a): contains a ConfigMap produced by IT operator to communicate some configuration to an application team
- more expirimentation.....