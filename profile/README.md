# "Actions adapter between their representation in a rule engine and cloud abstractions" - engineering thesis
This work is based on an [article](https://link.springer.com/article/10.1007/s10723-020-09532-0) describing the AMoCNA (Autonomic Management for Cloud-Native Applications) framework. 
The project's results can be seen [here](https://github.com/k8loud/demo).

## Objectives
- implement an adapter described as the Execution Controller in AMoCNA. It should be capable of executing predefined actions across various levels of cloud abstraction such as Cloud, Container Orchestrators, Cloud Native Applications
- create a library of actions executable by the adapter

## Components
- [themis-executor](https://github.com/k8loud/themis-executor) - the adapter (AMoCNA's Execution Controller)
- [kubernetes-lab-setup](https://github.com/k8loud/kubernetes-lab-setup) - environment setup (AMoCNA implementation)
- [Metrics-Deployment](https://github.com/k8loud/Metrics-Deployment) - Prometheus metrics translator (AMoCNA's Metrics Translator)
- [microservices-demo](https://github.com/k8loud/microservices-demo) - sample CNApp

## Authors
- [Paweł Gorgolewski](https://github.com/pgorgolew)
- [Paweł Pycia](https://github.com/Agwen12)
- [Przemysław Roman](https://github.com/proman3419)

with the supervision of dr inż. Joanna Kosińska
