---
title: Mesos, Docker Swarm and Kubernetes
---

<!--section -->
# Docker Swarm<br>Mesos<br>Kubernetes

<!-- .slide: class="master01" -->

---

## Docker Swarm

* Is a clustering tool for Docker containers
* Developed by Docker, Inc.
* Extends Docker to multiple hosts

---

## Docker Swarm

* Docker-centric
* Suitable for small clusters
* Low complexity

---

## Mesos

* Is a cluster manager
* Developed by the Apache Software Foundation
* Requires Marathon or Kubernetes to run containers
* DC/OS is a Mesos distribution including Marathon, developed by Mesosphere

---

## Mesos

* Supports mixed workloads: legacy, cloud-native, big data
* Suitable for large to very large clusters
* High complexity

---

## Kubernetes

* Is a container orchestrator
* Developed by Cloud Native Computing Foundation (Google, Red Hat, CoreOS, Microsoft, IBM, ...)
* Builds on 15 years of container experience at Google
* Supports Docker, Rkt, Windows Server Containers (Alpha)

---

## Kubernetes

* High level of portability (>5 public providers)
* Cluster federation (beta)
* Suitable for medium to large clusters
* Medium complexity

---

## Things to consider

* Business requirements match
* Product roadmap/future
* Networking model
* Storage types and management

---

## Things to consider

* Monitoring and log aggregation support
* Engineering overhead, e.g. for backup, monitoring, automation
* Operations and maintenance overhead
* Complexity of cluster upgrades

---

## Things to consider

* Vendor/provider lock-in
* Availability of consulting resources
* Community size

---

## Resources

* [Docker vs. Kubernetes vs. Apache Mesos<br>(Mesosphere Blog)](https://mesosphere.com/blog/docker-vs-kubernetes-vs-apache-mesos/)
* [Your Container Orchestration Needs<br>(Kubernauts Blog)](https://blog.kubernauts.io/your-container-orchestration-needs-kubernetes-vs-mesos-vs-docker-swarm-1efa9acb69be)
* [Cloud Native Computing Foundation](https://www.cncf.io/)

---

## OpenShift

* Developed by Red Hat
* Extends Kubernetes with:
  * Additional security
  * Certified base images

---

## OpenShift

* Extends Kubernetes with:
  * Build, deployment and scaling automation
  * CI/CD pipelines
  * Application centric networking
  * Dynamic storage provisioning
