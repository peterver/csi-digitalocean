## v0.1.0 (alpha) (UNRELEASED)

* Add method names to each log entry 
  [[GH-22]](https://github.com/digitalocean/csi-digitalocean/pull/22)
* Kubernetes deployment uses the `kube-system` namespace instead of the prior
  `default` namespace. Please make sure to delete and re-deploy the plugin.
  [[GH-21]](https://github.com/digitalocean/csi-digitalocean/pull/21)
* Change secret name from `dotoken` to `digitalocean`. Please make sure to
  update your keys (delete old secret and create new secret with name
  `digitalocean`). Checkout the README for instructions if needed.
  [[GH-21]](https://github.com/digitalocean/csi-digitalocean/pull/21)

## v0.0.1 (alpha)

* First release with all important methods of the CSI spec implemented
