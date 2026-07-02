# kubernetes-operations-handbook
A production-focused Kubernetes handbook covering architecture, operations, troubleshooting, failure scenarios, and real-world deployment practices.


## Repository Status

🚧 This repository is actively being developed.

The goal is to build a complete Kubernetes Operations Handbook covering Kubernetes architecture, workloads, networking, storage, security, troubleshooting, Amazon EKS, and production best practices through hands-on learning.

## About This Repository

Welcome to the Kubernetes Operations Handbook.

This repository documents my journey of learning Kubernetes from an operations perspective. Instead of collecting definitions or copying YAML manifests, this project focuses on understanding how Kubernetes works internally, deploying applications, troubleshooting failures, and following production-ready operational practices.

Every topic included in this repository is explored through hands-on practice, tested manifests, real troubleshooting scenarios, and detailed documentation. The objective is not only to learn Kubernetes concepts but also to understand how they are used by DevOps and Platform Engineers in real-world environments.

This repository will continuously evolve as I progress from Kubernetes fundamentals to advanced production concepts.

## Why I Built This Repository

While learning Kubernetes, I found that many repositories mainly contain copied notes, isolated YAML examples, or brief explanations from official documentation.

I wanted to build something different.

My goal is to create a repository that reflects how a Linux Engineer approaches Kubernetes in real environments by:

Understanding Kubernetes architecture instead of memorizing commands.
Learning how Kubernetes components interact behind the scenes.
Practicing deployments through hands-on labs.
Troubleshooting real Kubernetes failures.
Documenting production-oriented best practices.
Recording lessons learned throughout the learning journey.

This repository is intended to become an engineering handbook rather than a collection of notes.

## Engineering Principles

The following principles guide this repository:

-Every YAML manifest is tested before being committed.
-Every concept is validated through hands-on practice.
-Every topic includes practical deployment examples.
-Every issue encountered during practice is documented with its root cause and solution.
-Understanding Kubernetes internals is more valuable than memorizing commands.
-Production thinking is prioritized throughout the repository.
-Continuous learning and improvement are part of every topic.

## What Makes This Repository Different?

Unlike traditional Kubernetes learning repositories, this project focuses on operational understanding rather than theoretical notes.

Each topic includes:

- Why Kubernetes needs this resource
- Internal working
- Architecture diagrams
- YAML breakdown
- Hands-on labs
- Failure simulations
- Troubleshooting
- Production best practices
- Operator's Notes
- Interview Questions

## Repository Structure
kubernetes-operations-handbook/

├── 01-cluster-architecture/
├── 02-pods/
├── 03-replicasets/
├── 04-deployments/
├── 05-services/
├── 06-namespaces/
├── 07-configmaps/
├── 08-secrets/
├── 09-volumes/
├── 10-persistent-volumes/
├── 11-storage-classes/
├── 12-statefulsets/
├── 13-daemonsets/
├── 14-jobs/
├── 15-cronjobs/
├── 16-ingress/
├── 17-rbac/
├── 18-network-policies/
├── 19-resource-management/
├── 20-affinity-and-tolerations/
├── 21-helm/
├── 22-monitoring/
├── 23-logging/
├── 24-troubleshooting/
├── 25-aws-eks/
│
├── labs/
├── incident-reports/
├── runbooks/
├── diagrams/
├── scripts/
└── README.md


## Lab Environment
The practical exercises in this repository are performed using the following environment:

- Ubuntu Linux
- Docker
- Kubernetes
- kubectl
- AWS EC2
- Amazon EKS
- Git
- GitHub
- Visual Studio Code

## Future Enhancements

The repository will continue to expand with advanced Kubernetes topics, including:

Helm
Horizontal Pod Autoscaler (HPA)
Kubernetes Networking Deep Dive
Service Mesh Concepts
GitOps
Argo CD
CI/CD Integration
Advanced Troubleshooting Scenarios
Production Case Studies
High Availability
Disaster Recovery
Security Hardening

## License

This project is licensed under the MIT License. See the LICENSE file for additional information.

## Behind the Scenes

One unique aspect of this repository is the focus on understanding what happens inside Kubernetes after every command.

Instead of only learning how to create Kubernetes resources, this repository explains how different Kubernetes components interact internally.

For example:

kubectl apply

↓

API Server

↓

etcd

↓

Controller Manager

↓

Scheduler

↓

kubelet

↓

Container Runtime

↓

Running Application

## About this Journey

This repository represents my continuous journey toward becoming a proficient DevOps Engineer with strong Kubernetes operational knowledge.

The objective is not simply to learn Kubernetes resources, but to understand how Kubernetes behaves internally, how production workloads are managed, how failures are investigated, and how reliable systems are built and maintained.
