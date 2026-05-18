---



copyright:

  years: 2020, 2025
lastupdated: "2026-05-18"

keywords: ip address policy, ip ownership, bgp routing, client ip addresses, terms of use, IBM Cloud, ip addresses, IP address policy

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


# Understanding IBM Cloud IP address policy and ownership terms
{: #ip_address_policy}

Learn about IBM Cloud's IP address policy, including ownership terms, client-provided IP addresses, and BGP routing requirements for efficient IP utilization.
{: shortdesc}

## 1. IP Address Ownership
{: #ip_address_ownership}

International Business Machines Corporation or its subsidiaries that (IBM&reg;) own any IP addresses assigned to Client, which are to be used only with the Cloud Services. Use of the IP addresses terminates upon expiration or termination of a service, at which time the IP addresses will be reclaimed and may be re-issued to other customers in the future.

## 2. Client-Provided IP Addresses
{: #client_provided_ips}

Clients may provide their own IP addresses, subject to certain technical limitations and verification of ownership, by submitting a support case and providing a Letter of Authority to specify Client-owned IP prefixes. If IBM approves a request those IP addresses will be announced via Border Gateway Protocol (BGP) on the Client's behalf and routed to identified Client servers. Client retains ownership of those IP addresses. At Client's request, or upon cancellation of the services, IBM will cease to announce and route those IP addresses. While IBM will make reasonable efforts to ensure that BGP prefixes are accepted by all upstream ISPs, we cannot guarantee global reachability for Client-owned IPs.

## 3. Review / Justification / Efficiency Guidelines
{: #review_justification_efficiency}

Because IPv4 addresses are a scarce resource, client-provided IP addresses require ISPs to document that they are efficiently utilizing existing assigned addresses and are planning efficient utilization of any addresses being requested. RFC2050 promotes conservation and deters wasteful use or stockpiling of IP space. IBM is required to abide by these policies when IBM requests additional IP addresses to allocate. Therefore, when requested by IBM, Client provides information necessary to enable IBM to obtain IP addresses to support the Cloud Services.

All Client IP address requests are subjected to review by IBM to ensure efficient utilization and are not guaranteed to be approved. During the review, Client is required to provide details about how each IP address would be utilized and technical justification as to why additional IP addresses are needed. IBM may take steps to validate such information, including network scanning and server configuration inspection.

An initial review may take up to 2 business days, and depending on size and complexity, may require additional time for completion. Accounts with open abuse tickets will have their IP requests held for processing until all abuse issues have been resolved.
