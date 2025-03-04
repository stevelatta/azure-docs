---
title: OpenShift in Azure overview 
description: An overview of OpenShift in Azure.
author: haroldwongms
manager: mdotson
ms.service: virtual-machines
ms.subservice: openshift
ms.collection: linux
ms.topic: how-to
ms.workload: infrastructure
ms.date: 05/7/2019
ms.author: haroldw
---

# OpenShift in Azure

**Applies to:** :heavy_check_mark: Linux VMs :heavy_check_mark: Flexible scale sets 

OpenShift is an open and extensible container application platform that brings Docker and Kubernetes to the enterprise.  

OpenShift includes Kubernetes for container orchestration and management. It adds developer-centric and operations-centric tools that enable:

- Rapid application development.
- Easy deployment and scaling.
- Long-term lifecycle maintenance for teams and applications.

There are multiple versions of OpenShift available.  Of these versions, only two are available today for customers to deploy in Azure: OpenShift Container Platform and OKD (formerly OpenShift Origin).

## Azure Red Hat OpenShift

Microsoft Azure Red Hat OpenShift is a fully managed offering of OpenShift running in Azure. This service is jointly managed and supported by Microsoft and Red Hat. For more details, see the [Azure Red Hat OpenShift Service](../../openshift/index.yml) documentation.

## OpenShift Container Platform

Container Platform is an enterprise-ready [commercial version](https://www.openshift.com) from and supported by Red Hat. With this version, customers purchase the necessary entitlements for OpenShift Container Platform and are responsible for installation and management of the entire infrastructure.

Because customers "own" the entire platform, they can install it in their on-premises datacenter, or in a public cloud (such as Azure).

## OKD

OKD is an [open-source](https://www.okd.io/) upstream project of OpenShift that's community supported. OKD can be installed on CentOS or Red Hat Enterprise Linux (RHEL).

## Next steps

- [Configure common prerequisites for OpenShift in Azure](./openshift-container-platform-3x-prerequisites.md)
- [Deploy OpenShift Container Platform in Azure](./openshift-container-platform-3x.md)
- [Deploy OpenShift Container Platform Self-Managed Marketplace Offer](./openshift-container-platform-3x-marketplace-self-managed.md)
- [Deploy OpenShift in Azure Stack](./openshift-azure-stack.md)
- [Post-deployment tasks](./openshift-container-platform-3x-post-deployment.md)
- [Troubleshoot OpenShift deployment](./openshift-container-platform-3x-troubleshooting.md)
