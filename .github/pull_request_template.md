If the PR adds a new package:

- [ ] The package's schema URL is correct.
- [ ] The metadata file (e.g, `aws.yaml`), if present, contains: 
  - [ ] a supported category (`Cloud`, `Infrastructure`, `Network`, `Database`, `Monitoring`, or `Utility`).
  - [ ] a clear description.
  - [ ] a valid logo URL to an SVG whose dimensions align with existing packages.
  - [ ] a version number prefixed with `v` that corresponds with a valid GitHub release.
- [ ] The repo contains an Overview doc that includes:
  - [ ] a brief explanation of what the package is and what it does.
  - [ ] a representative example in all supported languages  .
- [ ] The repo contains an Installation and Configuration doc that includes:
  - [ ] links to SDKs in all supported languages.
  - [ ] a copyable command for installing the resource plugin if necessary.
  - [ ] an example of configuring the provider with `pulumi config set`.
  - [ ] an example of configuring the provider with environment variables.
- [ ] The @pulumi/docs team has review all documentation.
