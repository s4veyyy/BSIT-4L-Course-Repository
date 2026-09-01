# Google Cloud Platform (GCP) Research

## 1. Brief Overview

Google Cloud Platform (GCP), also known as Google Cloud, is a cloud computing platform developed by Google that provides a wide range of infrastructure, platform, data, networking, security, and artificial intelligence services. Google Cloud allows organizations and developers to build, deploy, manage, and scale applications using Google's global cloud infrastructure.

Google Cloud provides services for computing, object storage, databases, networking, data analytics, machine learning, artificial intelligence, application development, and containerized workloads. Organizations can combine these services to create solutions that match their technical and business requirements.

One of Google Cloud's major strengths is its integration with Google's expertise in data analytics, artificial intelligence, machine learning, networking, and large-scale infrastructure. It also provides managed services that can reduce the amount of infrastructure administration required from organizations.

---

## 2. Global Infrastructure

Google Cloud operates a global infrastructure organized into regions and zones. A region is an independent geographic area, while zones are isolated deployment areas within a region. Google Cloud resources can be deployed across different locations depending on requirements such as latency, availability, data residency, and application architecture.

Zones within the same region are connected through high-bandwidth and low-latency networks. Deploying workloads across multiple zones can help protect applications from failures affecting a single zone. Organizations can also distribute resources across multiple regions to provide additional failure independence and support disaster recovery.

Google Cloud's global network connects infrastructure around the world and is designed to provide reliable and low-latency connectivity. This global infrastructure allows organizations to deploy applications closer to their users and build highly available systems.

Google Cloud also provides specialized AI zones designed to provide high-capacity GPU and TPU resources for artificial intelligence and machine learning workloads.

---

## 3. Cloud Management Console

The Google Cloud console is a web-based graphical user interface used to manage Google Cloud projects, services, and resources. It provides a centralized environment where users can create and configure resources, monitor workloads, manage services, and access cloud management tools.

Google Cloud organizes resources using projects. A project contains the settings, permissions, resources, and other metadata associated with an application or workload. Users can select a project from the Google Cloud console and manage the resources associated with it.

In addition to the web-based console, Google Cloud provides the Google Cloud CLI, APIs, and client libraries. These tools allow developers and administrators to manage cloud resources through command-line interfaces, automation, and application code.

---

## 4. Four Core Services

### Compute Engine

Compute Engine is Google Cloud's infrastructure-as-a-service offering for running virtual machines and bare metal instances. It allows organizations to create and manage virtual machines running operating systems such as Linux and Windows.

Compute Engine provides configurable computing resources, storage options, and networking capabilities. Organizations can select machine configurations based on workload requirements and scale their computing resources as needed.

Compute Engine can be used for web servers, enterprise applications, development environments, batch processing, and high-performance computing workloads.

### Cloud Storage

Cloud Storage is Google Cloud's object storage service for storing and retrieving data in the cloud. It is designed to provide scalable and durable storage for different types of data.

Organizations can use Cloud Storage for application files, backups, archives, media files, data lakes, and other large datasets. Cloud Storage supports different storage classes that allow organizations to choose storage options based on data access patterns and cost requirements.

### Virtual Private Cloud (VPC)

Google Cloud Virtual Private Cloud (VPC) provides networking capabilities that allow organizations to connect and manage cloud resources in a controlled network environment.

VPC networks can be configured with subnets, IP addresses, firewall rules, routes, and other networking components. They allow resources such as Compute Engine virtual machines and other services to communicate securely.

Google Cloud VPC can also be integrated with on-premises environments, allowing organizations to build hybrid cloud architectures.

### Google Kubernetes Engine (GKE)

Google Kubernetes Engine (GKE) is a managed Kubernetes service that allows organizations to deploy, manage, and scale containerized applications. GKE provides Kubernetes capabilities while reducing the amount of infrastructure management required from users.

GKE can be used to run containerized applications, microservices, APIs, and other cloud-native workloads. It is useful for organizations adopting container orchestration and Kubernetes-based application architectures.

---

## 5. Three Advantages

### 1. Strong Data Analytics and Artificial Intelligence Capabilities

Google Cloud provides a broad range of services for data analytics, artificial intelligence, and machine learning. These capabilities make the platform suitable for organizations that need to process large datasets, develop machine learning applications, and build AI-powered solutions.

### 2. Global and High-Performance Infrastructure

Google Cloud operates a global infrastructure with regions, zones, and Google's global network. Organizations can distribute workloads geographically to reduce latency, improve availability, and support users in different locations.

### 3. Strong Support for Containers and Cloud-Native Applications

Google Cloud provides strong support for containerized and cloud-native applications through services such as Google Kubernetes Engine and Cloud Run. These services allow organizations to develop, deploy, and scale modern applications while reducing the need to manage underlying infrastructure manually.

---

## 6. Typical Enterprise Use Cases

Google Cloud can be used by enterprises for web and application hosting, data analytics, artificial intelligence, machine learning, containerized applications, database workloads, and large-scale data processing.

Organizations can use Compute Engine to run virtual machines and enterprise workloads, Cloud Storage to store large amounts of data, and Google Cloud networking services to connect and secure resources.

Google Cloud is also commonly suitable for organizations that require advanced data analytics and artificial intelligence capabilities. Services such as BigQuery can support large-scale data analytics, while Google Kubernetes Engine can support organizations developing and deploying containerized applications.

Google Cloud can also support global applications by allowing organizations to distribute workloads across multiple regions and zones. This can help reduce latency and improve application availability.

---

## 7. Screenshot

![Google Cloud Console](screenshots/gcp-homepage.png)

**Figure 1. Google Cloud Console**
