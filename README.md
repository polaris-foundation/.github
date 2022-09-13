# Polaris Foundation

The Polaris Foundation is an organisation responsible for maintaining the open-source Polaris platform for digital health products.

Polaris is a platform consisting of over 20 microservices, and is intended to be used as a backend for digital health products.

## Origin
The Polaris platform was created by Sensyne Health Ltd., and has now been made open-source. It was developed over several years from 2017-22 and was originally used as a backend for three digital health products in clinical use: two products for remote patient monitoring, and one for in-hospital monitoring.

Note that these digital health products are not themselves open-source - they remain proprietary. Only the Polaris platform itself has been made open source (MIT licence).

## CICD pipelines and packages
Wherever possible, CICD pipelines use public repositories to store packages. Various libraries are hosted on public pypi (Python) or npm (JavaScript) repositories. Polaris services are containerised and hosted on Github Container Registry.

Some services still rely on images and/or libraries that remain proprietary, and are not publicly available. Where applicable this is noted on the relevant service's README.

## Contributions
Contributions are welcomed from any source in the form of PRs.

## Contact
To get in touch, please email jondaly01 at gmail.com.
