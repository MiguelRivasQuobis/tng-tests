[![Join the chat at https://gitter.im/sonata-nfv/Lobby](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sonata-nfv/Lobby) 

<p align="center"><img src="https://github.com/sonata-nfv/tng-api-gtw/wiki/images/sonata-5gtango-logo-500px.png" /></p>

# 5GTANGO Integration Tests

This repository contains the integration tests as well as artifacts for the 5GTANGO components.

## Folder Structure

| Folder | Content | Responsible |
| --- | --- | --- |
|`pipeline/`| Jenkins pipeline scripts | - |
|`packages/`| Test NSDs, VNFDs, TSTDs to be packed to `*.tgo` packages | Manuel |
|`slice-descriptors/`| Slice descriptors for tests| ?? |
|`policies/`| Test Policies | Eleni |
|`slas/`| SLAs used for the tests | Marios, Evgenia?|
|...|...|...|


## Jenkins Integration

There is a Jenkins job to automatically build some of the artifacts stored in this repositry. For example, the Jenkins job automatically packages the SDK projects available in the `packages/` folder. The resulting `*.tgo` files are then available as [artifacts within Jenkins](TODO).

## Licensing

For licensing issues, please check the [Licence](https://github.com/sonata-nfv/tng-tests/blob/master/LICENSE) file.

#### Lead Developers

The following lead developers are responsible for this repository and have admin rights. They can, for example, merge pull requests.

* Felipe Vicens (felipevicens)
* Luis Hens (luishens01)