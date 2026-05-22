---

copyright:

  years: 2020, 2023

lastupdated: "2026-05-22"

keywords: shared responsibilities, ibm responsibilities, customer responsibilities, cloud security model, roles and responsibilities, shared responsibilities, IBM responsibility, customer responsibility

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Understanding shared responsibilities for IBM Cloud products and services
{: #shared-responsibilities}

Learn about the shared responsibilities between IBM and customers for managing IBM Cloud&reg; products, including operations, security, compliance, and disaster recovery tasks.
{: shortdesc}

In IBM Cloud&reg;, as is the case for other cloud service providers, the responsibilities for managing the lifecycle of, operating, and securing products are shared between IBM&reg; and the customer.

The responsibility of completing the following types of tasks on various products can be exclusive to IBM, the customer, or shared between the two. The tasks for each type of product are grouped in the following categories:

* Incident and operations management: Includes tasks such as monitoring, event management, high availability, problem determination, recovery, and full state backup and recovery.
* Change management: Includes tasks such as deployment, configuration, upgrades, patching, configuration changes, and deletion.
* Identity and access management: Includes tasks such as authentication, authorization, access control policies, and approving, granting, and revoking access.
* Security and regulation compliance: Includes tasks such as security controls implementation and compliance certification.
* Disaster recovery: Includes tasks such as providing dependencies on disaster recovery sites, provision disaster recovery environments, data and configuration backup, replicating data and configuration to the disaster recovery environment, and failover on disaster events.


When you're reviewing the following sections, the tables list resources for each category and who manages them. The following list describes what constitutes each type of resource in IBM Cloud.


Data
:   Customer-owned content that includes all data that is managed and controlled by the customer. Examples include information that is stored into volumes, files, and databases hosted on IBM Cloud resources and data processed, stored, and logged by the client applications hosted on IBM Cloud. It doesn't include client metadata, the information that is used by IBM to provide services to the customer and support and operate the client account, services, and resources that are always considered to be shared responsibility between client and IBM.

Applications
:   Customer-owned software components, such as executables, web applications, middleware, frameworks, libraries, and other software packages that the client developed or acquired by third parties and deployed in IBM Cloud.

Service instance
:   An entity that consists of resources that are reserved for a particular service.

Operating systems
:   The operating system software and configuration that are deployed in virtual or bare metal servers, such as Linux, Windows, or similar to the ones provided in [stock images](/docs/vpc?topic=vpc-about-images).

Virtual and bare metal servers
:   The virtual or bare metal servers that are ordered and managed through IBM Cloud services.

Virtual storage
:   The block, file, or Object Storage buckets ordered and managed through IBM Cloud.

Virtual network
:   Network resources such as VLAN, VPC, subnets, or IPs provided by [classic infrastructure](/docs/vlans?topic=vlans-getting-started) and [VPC](/docs/vpc?topic=vpc-about-networking-for-vpc) services that are ordered and managed through IBM Cloud.

Hypervisor
:   The software and configuration that is deployed in physical servers to host and manage the lifecycle of virtual servers.

Physical servers and memory
:   The physical compute devices and resources, such as cores, memory, and GPUs used to host the virtual or bare metal servers.

Physical storage
: The physical storage devices and resources, such as disks and storage devices that are used to host the virtual block, file, or Object Storage buckets.

Physical network and devices
:   The physical network devices and resources, such as switches, routers, gateways, firewalls, and load balancers that are used to host the virtual network resources.

Facilities and data centers
:   The physical data center buildings with power, cooling, and rooms for all the IBM Cloud physical equipment.


IBM Cloud supports the following types of products and the corresponding shared responsibility models. For more information about each specific service, see the documentation for that service.
{: note}

## Infrastructure-as-a-service
{: #iaas-services-responsibilities}

Infrastructure-as-a-service (IaaS) products that are managed by IBM are multi-tenant, accessed remotely, hosted on IBM physical infrastructure, created in customer-owned accounts, and have control plane and data plane security that is owned by IBM. Examples of this product type are Virtual Servers and Bare Metal Servers with the related block volumes that are connected to the customer account private subnets. You can find a list of these types of products in the IBM Cloud catalog on the Services tab. Each product is in an infrastructure subcategory within the Compute or VPC infrastructure categories.


| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Operating system | Customer | Customer | Customer | Customer | Customer |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | IBM | IBM | IBM | IBM | IBM |
| Physical servers and memory | IBM | IBM | Shared | Shared | IBM |
| Physical storage | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices | IBM | IBM | IBM | IBM | IBM |
| Facilities and data centers | IBM | IBM | IBM | IBM | IBM |
{: caption="Shared responsibilities for IaaS products" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and IBM is responsible for all underlying management. For disaster recover, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## IBM Hybrid Cloud
{: #hybrid-responsibilities}

IBM Hybrid Cloud products are managed by IBM, hosted on IBM-owned physical infrastructure, and located on-premises in customer-owned locations. An example of this product type is [Power Virtual Server Private Cloud](/docs/power-iaas?topic=power-iaas-private-cloud-architecture).

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Operating system | Customer | Customer | Customer | Customer | Customer |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | IBM | IBM | IBM | IBM | IBM |
| Physical servers and memory | IBM | IBM | Shared | Shared | IBM |
| Physical storage | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices: Top of rack and spine | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices: Datacenter core | Customer | Customer | Customer | Customer | Customer |
| Facilities and data centers | Customer | Customer | Customer | Customer | Customer |
{: caption="Shared responsibilities for hybrid cloud IaaS products" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and IBM is responsible for all underlying management. For disaster recover, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## Managed products
{: #managed-responsibilities}

Products that are managed by IBM require customer responsibilities only for the data or applications that customers add to the service. They are multi-tenant, accessed remotely, hosted on IBM virtual resources, created in IBM-owned accounts, and have control plane and data plane security that is owned by IBM. Examples of this product type are IBM Cloud databases or IBM Cloudant database instances. You can find a list of these types of products in the IBM Cloud catalog on the Services tab. However, any products that are listed in an infrastructure subcategory are infrastructure-as-a-service type products.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data |Customer  | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | IBM | IBM | IBM | IBM | Shared |
| Virtual and bare metal servers | IBM | IBM | IBM | IBM | IBM |
| Virtual storage | IBM | IBM | IBM | IBM | IBM |
| Virtual network | IBM | IBM | IBM | IBM | IBM |
| Hypervisor | IBM | IBM | IBM | IBM | IBM |
| Physical servers and memory | IBM | IBM | IBM | IBM | IBM |
| Physical storage | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices | IBM | IBM | IBM | IBM | IBM |
| Facilities and data centers | IBM | IBM | IBM | IBM | IBM |
{: caption="Shared responsibilities for fully-managed products" caption-side="top"}

For disaster recovery, IBM is responsible to ensure that other regions that are not impacted by the disaster are fully operational and will recover the impacted region by the disaster as quickly as possible.
{: note}

## Managed products on customer's resources
{: #managed-offerings-on-customers-resources-responsibilities}

Managed products on customer's resources are orchestrated by IBM. They are single-tenant and data plane products. They are accessed locally in customer accounts, data plane hosted on virtual resources in the customer's account, control plane security owned by IBM, and data plane security owned by the customer. IBM Cloud products of this type include IBM Cloud Kubernetes Service on classic infrastructure and Red Hat&reg; OpenShift&reg; on IBM Cloud&reg; on classic infrastructure.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Service instance | Shared | Shared | Shared | Shared | Shared |
| Operating system | Shared | Shared | Shared | Shared | Shared |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | IBM | IBM | IBM | IBM | IBM |
| Physical servers and memory | IBM | IBM | IBM | IBM | IBM |
| Physical storage | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices | IBM | IBM | IBM | IBM | IBM |
| Facilities and data centers | IBM | IBM | IBM | IBM | IBM |
{: caption="Shared responsibilities for self-managed products" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and IBM is responsible for all underlying management. For disaster recovery, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## Software packages
{: #software-packages}

Software packages are deployed by IBM as single tenant instances, and they are accessed locally in the customer account. The software instance is hosted on resources in the customer's accounts. The software deployment control plane security is owned by IBM, and the software instance security is owned by the customer.

A generic software deployment control plane manages the lifecycle of deployed software package instances. At a minimum, it manages the deployment, upgrade, and delete actions. As the packages become smarter, the generic control plane might also manage the start, stop, migration, scaling, monitoring, backup, and restore tasks.

You can find a list of software in the IBM Cloud catalog on the Software tab.

| Resource | Incident and Operations Management | Change Management | Identity and Access Management | Security and Regulation Compliance | Disaster Recovery |
| - | - | - | - | - | - |
| Data | Customer | Customer | Customer | Customer | Customer |
| Application | Customer | Customer | Customer | Customer | Customer |
| Software packages | Shared | Shared | Customer | Customer | Shared |
| Operating system | Shared | Shared | Customer | Customer | Shared |
| Virtual and bare metal servers | Shared | Shared | Shared | Shared | Shared |
| Virtual storage | Shared | Shared | Shared | Shared | Shared |
| Virtual network | Shared | Shared | Shared | Shared | Shared |
| Hypervisor | IBM | IBM | IBM | IBM | IBM |
| Physical servers and memory | IBM | IBM | IBM | IBM | IBM |
| Physical storage | IBM | IBM | IBM | IBM | IBM |
| Physical network and devices | IBM | IBM | IBM | IBM | IBM |
| Facilities and data centers | IBM | IBM | IBM | IBM | IBM |
{: caption="Shared responsiblities for software packages" caption-side="top"}

For areas marked as shared responsibilities, the customer is responsible for all the configurations, and IBM is responsible for all underlying management. For disaster recovery, the customer is responsible for creating resources in a secondary region and managing the application and data disaster recovery.
{: note}

## Deployable architectures
{: #deployable-architectures}

Deployable architectures can be comprised of infrastructure-as-a-service, managed products, and software. For more information about the specific responsibilities for you and for IBM when you use a deployable architecture, see [Understanding your responsibilities when using deployable architectures](/docs/secure-enterprise?topic=secure-enterprise-responsibilities-deployable-architectures).
