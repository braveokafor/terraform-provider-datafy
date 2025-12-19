# Provider Shim

Exposes internal provider for Pulumi Terraform Bridge.

## Usage

```go
import (
    pf "github.com/pulumi/pulumi-terraform-bridge/pf/tfbridge"
    datafyshim "github.com/datafy-io/terraform-provider-datafy/shim"
)

p := pf.ShimProvider(datafyshim.NewProvider())
```
