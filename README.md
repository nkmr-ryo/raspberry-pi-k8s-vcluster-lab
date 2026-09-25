# Raspberry Pi Kubernetes & vCluster Home Lab

A three-node Kubernetes home lab built on Raspberry Pi 5.

The goal of this project is to build a Kubernetes environment from scratch
and explore Kubernetes multi-tenancy with vCluster through hands-on experiments.

## Architecture

| Node | Role | Hardware |
|---|---|---|
| node1 | Control Plane | Raspberry Pi 5 |
| node2 | Worker | Raspberry Pi 5 |
| node3 | Worker | Raspberry Pi 5 |

## Software Stack

- Ubuntu Server 64-bit
- containerd
- Kubernetes
- Calico
- vCluster

## Project Roadmap

- [ ] Configure Raspberry Pi nodes
- [ ] Configure static networking
- [ ] Install and configure containerd
- [ ] Bootstrap Kubernetes cluster with kubeadm
- [ ] Install Calico CNI
- [ ] Deploy vCluster with Shared Nodes
- [ ] Explore resource synchronization between host and virtual clusters
- [ ] Deploy multiple isolated tenant clusters
- [ ] Explore KubeRay workloads on vCluster

## Documentation

Detailed setup procedures and experiment notes will be added under the `docs/` directory.

## Repository Structure

```text
.
├── README.md
├── docs/
├── configs/
└── manifests/

## Goals
- Kubernetes cluster bootstrapping and networking
- Kubernetes multi-tenancy
- vCluster architecture and resource synchronization
- Workload isolation
- AI infrastructure and KubeRay on multi-tenant Kubernetes