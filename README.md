# OpenAPI manifests for our APIs

### Directory structure:

```
openapi-manifests
│   README.md
└───manifests   
│   └───group1
|   |       orders_v1.yml
|   |       orders_v2.yml
|   |       products_v1.yml
|   └───group2
|           some_manifest_v1.yml
└───components
|       error_handling_v1.yml
```

### Description

- **manifests** - ready to denerate services from this manifests, folders inside **manifests** are groups of related APIs.
- **components** - some components from OAS3, ready to be referenced in other manifests by permalinks.

### Branches:
- **master** - production ready solutions, cannot be modified. If You want to introduce some changes to manifest, release new version.
- **develop** - can be modified at eny time, when ready, merge with **master**
