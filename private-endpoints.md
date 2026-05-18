---

copyright:
  years: 2021
lastupdated: "2026-05-18"

keywords: private connectivity, vpe for vpc, service endpoints, secure connections, service endpoints, private endpoints, virtual private endpoints, vpe, vpe for vpc

subcollection: overview

---

{:android: data-hd-operatingsystem="android"}
{:api: .ph data-hd-interface="api"}
{:audio: .audio}
{:attention: .attention}
{:authenticated-content: .authenticated-content}
{:beta: .beta}
{:c#: .ph data-hd-programlang="c#"}
{:cli: .ph data-hd-interface="cli"}
{:codeblock: .codeblock}
{:curl: .ph data-hd-programlang="curl"}
{:deprecated: .deprecated}
{:dotnet-standard: .ph data-hd-programlang="dotnet-standard"}
{:experimental: .experimental}
{:exception: .exception}
{:external: target="_blank" .external}
{:fast-path: .fast-path}
{:faq: data-hd-content-type="faq"}
{:generic: data-hd-programlang="generic"}
{:go: .ph data-hd-programlang="go"}
{:help: data-hd-content-type="help"}
{:here: .ph data-hd-vposition="here"}
{:hide-dashboard: .hide-dashboard}
{:hide-in-docs: .hide-in-docs}
{:important: .important}
{:ios: data-hd-operatingsystem="ios"}
{:java: .ph data-hd-programlang="java"}
{:javascript: .ph data-hd-programlang="javascript"}
{:middle: .ph data-hd-position="middle"}
{:node: .ph data-hd-programlang="node"}
{:note: .note}
{:objectc: .ph data-hd-programlang="Objective C"}
{:php: .ph data-hd-programlang="PHP"}
{:pre: .pre}
{:preview: .preview}
{:python: .ph data-hd-programlang="python"}
{:release-note: data-hd-content-type="release-note"}
{:remember: .remember}
{:requirement: .requirement}
{:restriction: .restriction}
{:right: .ph data-hd-position="right"}
{:row-headers: .row-headers}
{:ruby: .ph data-hd-programlang="ruby"}
{:screen: .screen}
{:shortdesc: .shortdesc}
{:step: data-tutorial-type="step"}
{:support: data-reuse="support"}
{:swift: .ph data-hd-programlang="swift"}
{:tag-security: .tag data-tag-color="red"}
{:tag-devops: .tag data-tag-color="magenta"}
{:tag-app: .tag data-tag-color="purple"}
{:tag-datastore: .tag data-tag-color="blue"}
{:tag-network: .tag data-tag-color="cyan"}
{:tag-observability: .tag data-tag-color="teal"}
{:tag-management: .tag data-tag-color="teal"}
{:tag-vpc: .tag data-tag-color="dark-teal"}
{:tag-compute: .tag data-tag-color="green"}
{:tag-ibm-cloud: .tag data-tag-color="blue"}
{:tag-cp4d: .tag data-tag-color="magenta"}
{:tag-iks: .tag data-tag-color="blue"}
{:tag-roks: .tag data-tag-color="red"}
{:tag-schematics: .tag data-tag-color="purple"}
{:tag-classic-inf: .tag data-tag-color="warm-gray"}
{:tag-satellite: .tag data-tag-color="magenta"}
{:tag-linux: .tag data-tag-color="red"}
{:tag-macos: .tag data-tag-color="cool-gray"}
{:tag-windows: .tag data-tag-color="cyan"}
{:tag-new: .tag data-tag-color="green"}
{:tag-updated: .tag data-tag-color="blue"}
{:tag-deprecated: .tag data-tag-color="red"}
{:tag-red: .tag data-tag-color="red"}
{:tag-magenta: .tag data-tag-color="magenta"}
{:tag-purple: .tag data-tag-color="purple"}
{:tag-blue: .tag data-tag-color="blue"}
{:tag-cyan: .tag data-tag-color="cyan"}
{:tag-teal: .tag data-tag-color="teal"}
{:tag-dark-teal: .tag data-tag-color="dark-teal"}
{:tag-green: .tag data-tag-color="green"}
{:tag-cool-gray: .tag data-tag-color="cool-gray"}
{:tag-warm-gray: .tag data-tag-color="warm-gray"}
{:term: .term}
{:terraform: .ph data-hd-interface="terraform"}
{:tip: .tip}
{:troubleshoot: data-hd-content-type="troubleshoot"}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:tsSymptoms: .tsSymptoms}
{:tutorial: data-hd-content-type="tutorial"}
{:ui: .ph data-hd-interface="ui"}
{:unity: .ph data-hd-programlang="unity"}
{:vbnet: .ph data-hd-programlang="vb.net"}
{:video: .video}


# Connecting to IBM Cloud services privately using virtual private endpoints
{: #endpoints-support}

Learn how to securely connect to IBM Cloud services using virtual private endpoints (VPE) for VPC and service endpoints for isolated connectivity and enhanced security.
{: shortdesc}

An increased focus on security is required by customers that use cloud-based services for production workloads. For many customers, accessing services in a secure manner is not only a sensible corporate policy, but in some cases required by compliance regulations. IBM&reg; has enhanced the connectivity options for customers who require isolated connectivity options for their workloads by providing the options of virtual private endpoints (VPE) for Virtual Private Cloud (VPC) and IBM Cloud&reg; service endpoints.

To interact with the product APIs, you can use public endpoints, VPE for VPC, or service endpoints.

* Public endpoints: You can connect to resources in all regions in your account over the IBM Cloud public network.
* VPE for VPC: After you create private endpoints in your VPC, you can connect by using a private IP address that's accessible only from your VPC. This option is available for VPC users.
* Service endpoints: After you enable virtual routing and forwarding (VRF) and turn on service endpoints for your account, you can connect by using a private IP address that's accessible only through the IBM Cloud private network. This option is available for classic infrastructure users.

By using VPE for VPC or service endpoints, you can privately connect to IBM Cloud platform services and service products in the catalog that support this type of private connectivity.

Go to the [API docs](https://{DomainName}/docs?tab=api-docs) for the service that you want to connect to and see the Endpoint URLs section to view the endpoints for that service.
{: tip}

## Virtual private endpoints for VPC
{: #vpe-overview}

VPE for VPC provides private connectivity to select IBM Cloud services originating from the VPC network of your choosing, without traversing the public backbone. All connectivity is contained within IBM Cloud. By using a service that supports VPE for VPC, you can connect to the service from your VPC network by assigning the IP address of your choosing, which is allocated from a subnet within your VPC.

VPEs are virtual IP interfaces that are bound to an endpoint gateway created on a per service or service instance basis, depending on the service operation model. The endpoint gateway is a virtualized function that scales horizontally, is redundant and highly available, and spans all availability zones of your VPC. Endpoint gateways enable communications from virtual server instances in your VPC to IBM Cloud services, with all traffic going over the IBM Cloud backbone. VPE for VPC gives you the experience of controlling all the private addressing within your cloud.

For more information, see [About virtual private endpoint gateways](/docs/vpc?topic=vpc-about-vpe).


## IBM Cloud service endpoints
{: #cloud-service-endpoints-overview}

For classic infrastructure users, the cloud service endpoints feature provides the option of using private routes to connect to IBM Cloud services. These private routes are not accessible or reachable over the internet. You can protect your data from threats from the public network and logically extend your private network. This capability enables an enterprise with strict security requirements to have confidence in moving workloads to the IBM public cloud.

For more information, see [Enabling virtual routing and forwarding (VRF) and service endpoints](/docs/account?topic=account-vrf-service-endpoint).
