# effective-range-api
Public API of the Effective Range systems

## Validation

CI validates the OpenAPI specification on pull requests and pushes to `main`,
and on version tag pushes. Releases are published only after validation passes.

## Releases

Push a version tag such as `v0.2.0` to create a GitHub Release with the original
OpenAPI YAML and its JSON equivalent as release assets:

- `effective-range-api_0.2.0.yaml`
- `effective-range-api_0.2.0.json`
