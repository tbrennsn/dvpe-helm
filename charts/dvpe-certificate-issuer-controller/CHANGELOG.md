# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.3]
### Fixed
* Cluster issuer secret source parameterized (`issuercontroller.externalsecrets.clusterIssuer`)

### Deprecated
* `issuercontroller.externalsecrets.name` - rename to `issuercontroller.externalsecrets.dockerCredentials`

## [0.2.1]
### Fixed
* Tag of the issuer

## [0.2.0]
### Added
* ClusterIssuer resource and RBAC adjustments
* Global CLCM secret

## [0.1.0]
### Changed
* Update Deployment resources
* Use namespace service account 
* Fix some naming issues

## [0.0.4]

### Changes

* Fix container name value bug 

## [0.0.3]

### Changes

* Simplify rbac template file

## [0.0.2]

### Added

* Missing CRD
* RBAC Permissions
* External Secret

### Changes

* Increased memory limits to 300mb for issuer-manager pod 

## [0.0.1]

### Added

* Initial Version
* Contains K8S Resources: Deployment and ExternalSecret

[0.0.1]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.0.1/charts/dvpe-certificate-issuer-controller
[0.0.2]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.0.2/charts/dvpe-certificate-issuer-controller
[0.0.3]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.0.3/charts/dvpe-certificate-issuer-controller
[0.0.4]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.0.4/charts/dvpe-certificate-issuer-controller
[0.1.0]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.1.0/charts/dvpe-certificate-issuer-controller
[0.2.0]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.2.0/charts/dvpe-certificate-issuer-controller
[0.2.1]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.2.1/charts/dvpe-certificate-issuer-controller
[0.2.3]: https://github.com/DVPE-cloud/dvpe-helm/tree/dvpe-certificate-issuer-controller-0.2.3/charts/dvpe-certificate-issuer-controller
