# effective-range-api
Public API of the Effective Range systems

## Validation

CI validates the OpenAPI specification on pull requests and pushes to `main`,
on version tag pushes, and when a GitHub Release is published. Release assets
are uploaded only after validation passes.

## Releases

Push a version tag such as `v0.2.0`, or publish a release for that tag on GitHub.
The tag version must match `info.version` in the OpenAPI specification.
CI creates a release if needed, replaces existing release notes with generated
notes, and uploads the original OpenAPI YAML and its JSON equivalent as release
assets (replacing assets with the same names):

- `effective-range-api_0.2.0.yaml`
- `effective-range-api_0.2.0.json`
