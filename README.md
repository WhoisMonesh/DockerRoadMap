# Docker Learning Roadmap (v1.5 January 2025)

[![Check Markdown links](https://github.com/Evalle/DCA/actions/workflows/action.yml/badge.svg)](https://github.com/Evalle/DCA/actions/workflows/action.yml)
[![Sparkline](https://stars.medv.io/evalle/dca.svg)](https://stars.medv.io/evalle/dca)

## Table of Contents
1. [Core Docker Concepts](#1-core-docker-concepts)
2. [Image Management](#2-image-management)
3. [Orchestration](#3-orchestration)
4. [Networking](#4-networking)
5. [Security](#5-security)
6. [Storage](#6-storage)
7. [Installation & Configuration](#7-installation--configuration)
8. [Exam Preparation](#8-exam-preparation)

---

## 1. Core Docker Concepts

### Docker Architecture
- [Docker Overview](https://docs.docker.com/get-started/overview/)
- [Namespaces & cgroups](https://docs.docker.com/get-started/overview/#the-underlying-technology)
- [Docker Engine](https://docs.docker.com/engine/)

### Containers vs VMs
- [Container Basics](https://www.docker.com/resources/what-container)
- [Comparison Guide](https://www.docker.com/blog/containers-replacing-virtual-machines/)

**Additional Resources:**
- [Docker 101 Tutorial](https://www.docker.com/101-tutorial)
- [Play with Docker Labs](https://labs.play-with-docker.com/)

---

## 2. Image Management

### Dockerfiles
- [Dockerfile Reference](https://docs.docker.com/engine/reference/builder/)
- [Best Practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)

### Image Operations
- [Managing Images](https://docs.docker.com/engine/reference/commandline/image/)
- [Multi-stage Builds](https://docs.docker.com/develop/develop-images/multistage-build/)

### Registries
- [Working with Registries](https://docs.docker.com/registry/)
- [Docker Hub](https://hub.docker.com/)
- [MSR (Mirantis Secure Registry)](https://www.mirantis.com/software/mirantis-secure-registry/)

**Additional Resources:**
- [Dockerfile Linter](https://hadolint.github.io/hadolint/)
- [Image Security Scanning](https://docs.docker.com/engine/scan/)

---

## 3. Orchestration

### Swarm Mode
- [Swarm Tutorial](https://docs.docker.com/engine/swarm/swarm-tutorial/)
- [Services & Stacks](https://docs.docker.com/engine/swarm/services/)

### Kubernetes
- [Docker & Kubernetes](https://docs.docker.com/get-started/kube-deploy/)
- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)

**Additional Resources:**
- [Swarm Visualizer](https://github.com/dockersamples/docker-swarm-visualizer)
- [Kompose (Docker-compose to K8s)](https://kompose.io/)

---

## 4. Networking

### Network Models
- [Container Network Model](https://docs.docker.com/network/)
- [Kubernetes Networking](https://kubernetes.io/docs/concepts/cluster-administration/networking/)

### Practical Networking
- [Bridge Networks](https://docs.docker.com/network/network-tutorial-standalone/)
- [Overlay Networks](https://docs.docker.com/network/overlay/)

**Additional Resources:**
- [Docker Networking Deep Dive](https://success.docker.com/article/networking)
- [Traefik Load Balancer](https://doc.traefik.io/traefik/)

---

## 5. Security

### Docker Security
- [Content Trust](https://docs.docker.com/engine/security/trust/)
- [Secrets Management](https://docs.docker.com/engine/swarm/secrets/)

### Kubernetes Security
- [RBAC](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [ConfigMaps & Secrets](https://kubernetes.io/docs/concepts/configuration/)

**Additional Resources:**
- [CIS Docker Benchmark](https://www.cisecurity.org/benchmark/docker/)
- [Notary Project](https://github.com/theupdateframework/notary)

---

## 6. Storage

### Storage Drivers
- [Select Storage Driver](https://docs.docker.com/storage/storagedriver/select-storage-driver/)

### Volumes
- [Manage Volumes](https://docs.docker.com/storage/volumes/)
- [Persistent Storage in K8s](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)

**Additional Resources:**
- [Rex-Ray Volume Plugin](https://rexray.readthedocs.io/en/stable/)
- [Portworx Storage](https://portworx.com/)

---

## 7. Installation & Configuration

### Installation
- [Install Docker Engine](https://docs.docker.com/engine/install/)
- [Post-install Steps](https://docs.docker.com/engine/install/linux-postinstall/)

### Enterprise Setup
- [MKE Installation](https://docs.mirantis.com/mke/3.5/install/)
- [MSR Installation](https://docs.mirantis.com/msr/2.9/install/)

**Additional Resources:**
- [Docker Bench for Security](https://github.com/docker/docker-bench-security)
- [Ansible Docker Role](https://galaxy.ansible.com/geerlingguy/docker)

---

## 8. Exam Preparation

### Practice Materials
- [Official Study Guide](https://a.storyblok.com/f/146871/x/2001ce939c/docker-study-guide_v1-5-jan-2025.pdf)
- [Practice Questions](https://github.com/bbachi/DCA-Practice-Questions)

### Exam Details
- [Schedule Exam](https://prod.examity.com/docker)
- [Exam Objectives](https://training.mirantis.com/dca-certification-exam/)

**Additional Resources:**
- [DCA Exam Simulator](https://www.udemy.com/course/docker-certified-associate-practice-tests/)
- [Docker Community Slack](https://dockercommunity.slack.com/)

---

## Learning Path Recommendation

1. Start with Core Concepts (2 weeks)
2. Master Image Management (2 weeks)
3. Learn Orchestration (3 weeks)
4. Study Networking (2 weeks)
5. Focus on Security (2 weeks)
6. Understand Storage (1 week)
7. Practice Installation (1 week)
8. Exam Preparation (2 weeks)

**Total recommended study time:** 15 weeks (adjust based on experience)

---

## Contributors

Thanks to all [contributors!](https://github.com/Evalle/DCA/graphs/contributors)
