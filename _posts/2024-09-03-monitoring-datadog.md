---
title: "Monitoring azure applications with Datadog"
date: 2024-09-03 00:00:00 +0300
categories: [Datadog, Azure, Kubernetes]
tags: [containers, azure, linux, opentelemetry]
---

In this article, we'll delve into the advantages of using Azure Kubernetes Service (AKS) and identify the essential health and performance metrics to monitor when utilizing the service. 

Following that, we'll discuss how a platform like Datadog can be employed to collect these metrics, along with other monitoring data such as distributed request traces and logs, to gain comprehensive visibility into your containerized applications

## How does AKS works?
Azure Kubernetes Service (AKS) is a managed service for running Kubernetes, the open-source container orchestration platform originally developed by Google.

![Desktop View](/assets/img/kubernetes-logo.png){: width="500"}
_note. kubernetes logo_

Kubernetes automates various tasks related to deploying, managing, and scaling containerized workloads. 

Beyond distributing workloads across nodes in a cluster, Kubernetes can automatically scale them based on real-time demand. 

It also enhances the availability of mission-critical applications by automatically restarting unhealthy containers and nodes as needed.

Despite its many advantages, Kubernetes has a steep learning curve (i'm currently learning too XD). This is where managed services like AKS prove valuable.

## How to monitor Azure Kubernetes Service
When using AKS, you need continuous visibility across every layer of your environment. 

This includes all of your hosts, containers, and apps, as well as the orchestrator that manages all of these components.

To get high-level insight into your AKS environment, you'll want to monitor the status of the objects in your cluster and ensure that nodes and other services are able to communicate efficiently with the control plane. 

## How to monitor Azure container environments with Datadog

![Desktop View](/assets/img/datadog-logo.png){: width="500"}
_note. datadog logo_

Datadog integrates with hundreds of popular technologies—including the entire suite of Azure services—to give you complete visibility into your infrastructure and applications. 

You can set up Datadog to monitor every layer of your environment, including:

1.    Azure Kubernetes Service nodes, pods, and containers
1.    Containerized web apps running in Azure App Service plans
1.    All of the Azure services that support your container apps, including Azure DevOps, Azure SQL Database, and Azure VM Scale Sets

Whether you are using App Service or AKS, Datadog provides deep visibility into your containerized applications with out-of-the-box integrations and the Datadog Agent. 

## Full visibility into containerized applications

Azure Kubernetes Service (AKS) enables organizations to build and deploy containerized applications at scale without the need to manage their own control plane. 

Alternatively, Azure App Service offers a way to run containerized web applications without requiring a container orchestration technology like Kubernetes. 

Regardless of the deployment method, monitoring the health and performance of your containerized applications is essential for delivering an optimal user experience.

Datadog's out-of-the-box visualizations provide unified insights into every layer of your stack, allowing you to detect and troubleshoot issues before they escalate into user-facing incidents. 

Automated alerts further assist in investigating and resolving problems, enhancing the reliability, performance, and security of your containerized applications as they evolve and scale.
