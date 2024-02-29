# OTLP Tail Sampling Module

Module to ingest OTLP traces and apply tail sampling policies.

## Agent Version

`>= v0.40.0`

## Module arguments

...

## Module exports

...

## Example

```
module.git "otlp_load_balancer" {
  repository = "https://github.com/rlankfo/agent-modules.git"
  revision   = "main"
  path       = "modules/otlp/load-balancer/module.river"

  arguments {
    service_endpoint = "tail-sampler.default.svc.cluster.local"
  }
}
```
