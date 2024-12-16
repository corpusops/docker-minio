# library images on steroids for library/minio

DISCLAIMER
============

**UNMAINTAINED/ABANDONED CODE / DO NOT USE**

Due to the new EU Cyber Resilience Act (as European Union), even if it was implied because there was no more activity, this repository is now explicitly declared unmaintained.

The content does not meet the new regulatory requirements and therefore cannot be deployed or distributed, especially in a European context.

This repository now remains online ONLY for public archiving, documentation and education purposes and we ask everyone to respect this.

As stated, the maintainers stopped development and therefore all support some time ago, and make this declaration on December 15, 2024.

We may also unpublish soon (as in the following monthes) any published ressources tied to the corpusops project (pypi, dockerhub, ansible-galaxy, the repositories).
So, please don't rely on it after March 15, 2025 and adapt whatever project which used this code.



## Wrapped images
- [docker-images](https://github.com/corpusops/docker-images) compatibles images (original images wrapped with tools)
- [![.github/workflows/cicd.yml](https://github.com/corpusops/docker-minio/workflows/.github/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/corpusops/docker-minio/actions?query=workflow%3A.github%2Fworkflows%2Fcicd.yml+branch%3Amain)

| original   | wrapped  |
|------------|-----------|
| [minio/k8s-operator](https://hub.docker.com/r/minio/k8s-operator)([./minio/k8s-operator](./minio/k8s-operator))                 | [corpusops/minio-k8s-operator](https://hub.docker.com/r/corpusops/minio-k8s-operator)       |
| [minio/doctor](https://hub.docker.com/r/minio/doctor)([./minio/doctor](./minio/doctor))                                         | [corpusops/minio-doctor](https://hub.docker.com/r/corpusops/minio-doctor)                   |
| [minio/mint](https://hub.docker.com/r/minio/mint)([./minio/mint](./minio/mint))                                                 | [corpusops/minio-mint](https://hub.docker.com/r/corpusops/minio-mint)                       |
| [minio/minio](https://hub.docker.com/r/minio/minio)([./minio/minio](./minio/minio))                                             | [corpusops/minio](https://hub.docker.com/r/corpusops/minio)                     |
| [minio/mc](https://hub.docker.com/r/minio/mc)([./minio/mc](./minio/mc))                                                         | [corpusops/mc](https://hub.docker.com/r/corpusops/mc)                           |
