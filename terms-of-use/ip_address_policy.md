---



copyright:

  years: 2020, 2025
lastupdated: "2026-05-22"

keywords: ip address policy, ip ownership, bgp routing, client ip addresses, terms of use, IBM Cloud, ip addresses, IP address policy

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Understanding IBM Cloud IP address policy and ownership terms
{: #ip_address_policy}

Learn about IBM Cloud's IP address policy, including ownership terms, client-provided IP addresses, and routing requirements for efficient IP utilization.
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
