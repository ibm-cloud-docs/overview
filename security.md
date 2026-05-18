---

copyright:
  years: 2017, 2024
lastupdated: "2026-05-18"

keywords: ibm cloud security, data protection, secure engineering, compliance programs, security controls, platform security, compliance, penetration testing, quantum computing, data at rest, data in transit, cryptography

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


# IBM Cloud security and data protection
{: #security}

Learn how IBM Cloud ensures data security with layered controls, secure engineering, compliance programs, and quantum-safe cryptography for data at rest and in transit.
{: shortdesc}

Designed with secure engineering practices, the IBM Cloud&reg; platform provides layered security controls across network and infrastructure. IBM Cloud focuses on protection across the entirety of the compute lifecycle, which includes everything from the build process and key management to the security of data services. IBM Cloud also provides a group of security services that can be used by application developers to secure their mobile and web apps. These elements combine to make IBM Cloud a platform with clear choices for secure application development.

In addition to our own diligence in creating and operating a secure cloud, IBM&reg; also engages many different firms to assess the security and compliance of our cloud platform. For more information, see [IBM Cloud compliance programs](https://www.ibm.com/products/cloud/compliance) for a detailed list of certifications and attestations.

IBM Cloud ensures security readiness by adhering to security policies that are driven by best practices in IBM for systems, networking, and secure engineering. These policies include practices such as source code scanning, dynamic scanning, threat modeling, and penetration testing. IBM Cloud follows the IBM Product Security Incident Response Team (PSIRT) process for security incident management. See the [IBM Security Vulnerability Management (PSIRT)](https://www.ibm.com/trust/security-vulnerability-management){: external} site for details.

In addition to the regular penetration testing conducted by IBM and our partners, you can conduct penetration testing of your VPC or Classic Infrastructure resources on IBM Cloud. Prior authorization to do so is not required by IBM Cloud. IBM Cloud customers under an active NDA can request a copy of a penetration testing executive summary by [opening a support case](/unifiedsupport/supportcenter).

For more details about security for your applications and environments in IBM Cloud, see [Security for IBM Cloud](https://www.ibm.com/products/cloud/security){: external}.

## Quantum safe data protection
{: #quantum}

Quantum computing promises to solve complex problems that even the most powerful computers can't solve today. At the same time, there is risk that data protected by public key cryptosystems could be recorded today and decrypted years later by using a Cryptographically Relevant Quantum Computer (CRQC). The IBM Cloud platform provides a secure, reliable, and cost-effective cloud computing environment that's tailored to your specific business needs. With security at the core, IBM Cloud offers capabilities that you can use to integrate your apps and tools with the required level of data protection.

With a focus on the prioritization of workload protection, IBM Cloud includes the following core features that you can leverage at rest and in transit for inbound and outbound traffic.

### Data at rest
{: #data-at-rest}

Key management, using Key Protect and Hyper Protect Crypto Services, supports large key sizes that are considered quantum safe for data encryption (Data Encryption Key) and envelope encryption (Key Encryption Key). For more details, see [Protecting data with envelope encryption](/docs/key-protect?topic=key-protect-envelope-encryption) and [Bringing your encryption keys to the cloud](/docs/hs-crypto?topic=hs-crypto-importing-keys).

### Data in transit
{: #data-in-transit}

Key Protect supports quantum safe enabled TLS connections through a hybrid method that combines Quantum Safe Cryptography and current ECC algorithms. Key Protect uses the [Kyber algorithm](https://pq-crystals.org/kyber/index.shtml){: external} with NIST evaluation round three parameters. See [Introduction to Quantum-safe Cryptography in TLS](/docs/key-protect?topic=key-protect-quantum-safe-cryptography-tls-introduction) for more details.

Secure your outbound data with post-quantum support on IBM Cloud Internet Services. See [Bringing post-quantum cryptography to IBM's edge](https://community.ibm.com/community/user/blogs/kevin-schroeder/2024/07/24/ibm-edge-post-quantum){: external} for more details.

For cloud native apps, TLS connections are quantum safe enabled with a custom ingress controller for IBM Cloud Kubernetes Service and a custom router for Red Hat OpenShift on IBM Cloud.

### Authentication
{: #data-auth}

A high-security version of round 2 Dilithium digital signatures in Hyper Protect Crypto Services is primarily used for data integrity, authenticity, and non-repudiation. See [Post-quantum cryptography support](/docs/hs-crypto?topic=hs-crypto-what-new#hs-crypto-8june2022) for more details.
