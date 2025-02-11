---
hide:
  - toc
authors:
  - rosinec
  - michal-ruzicka
  - matejantol
---

!!! warning "The log-in method to the SensitiveCloud service has been changed"

    On February 26th, 2023, the SensitiveCloud's login method has been changed from the MUNI Login to e-INFRA CZ Login.

    [Read more how it affects users and security][migration]

SensitiveCloud is a computing and storage environment for working with sensitive data. This environment is primarily designed for research in academia, especially in the life sciences and medicine; however, its use is also suitable for sensitive data processing in other areas. For the definition of the processes and the technical design of the environment, the requirements arising from the ISO 27000 family of standards are used; then C5, ISO 15189 and ECRIN.

The environment is built on modern container technology using Kubernetes platform (K8s). It provides a high level of scalability, dynamic environment and other features such as GPU acceleration of computations. Users can choose whether to use one of the predefined containers with frequently used applications or to containerise their applications themselves.

[Read more at SensitiveCloud product page][1]

## Getting Access to SensitiveCloud

If you want to use the SensitiveCloud services and you are a principal investigator (PI), ask to be allocated a computing time in the SensitiveCloud. The PI should be a research group/activity leader, and is responsible for the access to the data and utilization of computing time.

- [Requesting project in SensitiveCloud][2]    
- [Manage access to the project in SensitiveCloud][3]

## Using SensitiveCloud

Let’s deep into the technical aspects of working with SensitiveCloud. This section is dedicated to anyone, who will be deploying its computing job or run applications.

- [Connecting to the SensitiveCloud management][4]
- [Working with the SensitiveCloud][5]
- Deploying applications in the SensitiveCloud (TODO)

## Learn More

> The SensitiveCloud environment is provided by CERIT-SC, which is an organisational unit of the Institute of Computing at Masaryk University and one of the three members of the large research infrastructure e-INFRA CZ.

[1]: https://cerit-sc.cz/infrastructure-services/trusted-environment-for-sensitive-data
[2]: ./get-project
[3]: ./manage-project
[4]: ./getting-started/connecting-to-sensitive-cloud
[5]: https://docs.cerit.io

[migration]: ./migration-from-muni.md
