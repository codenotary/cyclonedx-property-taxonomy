# Codenotary CycloneDX Property Taxonomy, v0.0.1

This is the official Codenotary property taxonomy for CycloneDX.

For more information about CycloneDX property taxonomies, refer to
their [official documentation](https://github.com/CycloneDX/cyclonedx-property-taxonomy).

## `codenotary` Namespace Taxonomy

| Namespace | Description |
| --- | --- |
| `codenotary:trust_status` | Namespace for properties specific to trust status. | 

## `codenotary:trust_status` Namespace Taxonomy

| Property | Description | Example values |
| --- | --- | --- |
| `codenotary:trust_status:level` | Assigned level of trust. | `trusted`, `untrusted`, `unsupported`, `unknown` |
| `codenotary:trust_status:signer` | The id of trust author. | `Joe` |
| `codenotary:trust_status:comment` | Additional information related to status. | `Before release` |
| `codenotary:trust_status:timestamp` | Time when level of trust was assigned, in UTC. | `2023-02-15T07:48:39Z` |