DigiCert Issuer
---------------

[External Issuer](https://cert-manager.io/docs/configuration/external) extending the [cert-manager](https://cert-manager.io) with the [DigiCert cert-central API](https://dev.digicert.com/services-api/orders/).

# Prerequisites

The cert-manager needs to be installed in the selected cluster.

# Installation & Configuration

Use the [Kustomize resources](config) or run `make deploy`.

# Documentation & Examples

For additional information see the [API documentation](docs/apidocs/api.md) and the provided [samples](config/samples).