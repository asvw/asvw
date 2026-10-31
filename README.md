Fixes for issues found while live validating Kubernetes labs end to end against the code and the docs. Merged upstream since October 2026:

**kubernetes/kubernetes**
- `kubeadm upgrade diff` and `--dry-run` now show the etcd manifest ([#143604](https://github.com/kubernetes/kubernetes/pull/143604))

**kubernetes/website**
- The documented etcd restore now survives the next kubeadm upgrade ([#58373](https://github.com/kubernetes/website/pull/58373))
- The kubeadm implementation details page describes the API server's kubelet access as of v1.37 ([#58356](https://github.com/kubernetes/website/pull/58356), [#58390](https://github.com/kubernetes/website/pull/58390))

**kubernetes/examples**
- The guestbook example runs again ([#598](https://github.com/kubernetes/examples/pull/598))

**cilium/cilium**
- `cilium sysdump` collects CIDR groups again ([#49914](https://github.com/cilium/cilium/pull/49914))

Still open, from the same work: [pull requests](https://github.com/search?q=is%3Aopen+author%3Aasvw+org%3Akubernetes+org%3Acilium&type=pullrequests).
