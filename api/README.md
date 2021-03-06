## Ignite API

The Ignite API types use the [`k8s.io/apimachinery`](https://github.com/kubernetes/apimachinery) framework, and
similar conventions as the Kubernetes API types. That said, the Ignite API types don't (at the moment at least)
have any connection or depend on Kubernetes itself in any way.

The API types are used for two primary things:

 - Letting end users [declaratively specify advanced configuration](../docs/declarative-config.md) (e.g. `ignite create --config`)
 - Persisting internal data on disk in a standardized way.

Please refer to the (autogenerated) docs for the API types:

 - `ignite.weave.works/v1alpha1` in [ignite.md](ignite.md)
 - The meta-package containing generic types [meta.md](meta.md)
