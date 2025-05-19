---

copyright:
  years: 2017, 2024
lastupdated: "2025-05-15"

keywords: security controls, platform security, compliance, penetration testing, quantum computing, data at rest, data in transit, cryptography

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# How do I know that my data is safe?
{: #security}

Designed with secure engineering practices, the {{site.data.keyword.cloud}} platform provides layered security controls across network and infrastructure. {{site.data.keyword.cloud_notm}} focuses on protection across the entirety of the compute lifecycle, which includes everything from the build process and key management to the security of data services. {{site.data.keyword.cloud_notm}} also provides a group of security services that can be used by application developers to secure their mobile and web apps. These elements combine to make IBM Cloud a platform with clear choices for secure application development.
{: shortdesc}

In addition to our own diligence in creating and operating a secure cloud, {{site.data.keyword.IBM}} also engages many different firms to assess the security and compliance of our cloud platform. For more information, see [{{site.data.keyword.cloud_notm}} compliance programs](https://www.ibm.com/cloud/compliance) for a detailed list of certifications and attestations.

{{site.data.keyword.cloud_notm}} ensures security readiness by adhering to security policies that are driven by best practices in {{site.data.keyword.IBM_notm}} for systems, networking, and secure engineering. These policies include practices such as source code scanning, dynamic scanning, threat modeling, and penetration testing. {{site.data.keyword.cloud_notm}} follows the {{site.data.keyword.IBM_notm}} Product Security Incident Response Team (PSIRT) process for security incident management. See the [{{site.data.keyword.IBM_notm}} Security Vulnerability Management (PSIRT)](https://www.ibm.com/trust/security-vulnerability-management){: external} site for details.

In addition to the regular penetration testing conducted by {{site.data.keyword.IBM_notm}} and our partners, you can conduct penetration testing of your VPC or Classic Infrastructure resources on {{site.data.keyword.cloud_notm}}. Prior authorization to do so is not required by {{site.data.keyword.cloud_notm}}. {{site.data.keyword.cloud_notm}} customers under an active NDA can request a copy of a penetration testing executive summary by [opening a support case](/unifiedsupport/supportcenter).

For more details about security for your applications and environments in {{site.data.keyword.Bluemix_notm}}, see [Security for {{site.data.keyword.cloud_notm}}](https://www.ibm.com/cloud/security){: external}.

## Quantum safe data protection
{: #quantum}

Quantum computing promises to solve complex problems that even the most powerful computers can't solve today. At the same time, there is risk that data protected by public key cryptosystems could be recorded today and decrypted years later by using a Cryptographically Relevant Quantum Computer (CRQC). The {{site.data.keyword.cloud_notm}} platform provides a secure, reliable, and cost-effective cloud computing environment that's tailored to your specific business needs. With security at the core, {{site.data.keyword.cloud_notm}} offers capabilities that you can use to integrate your apps and tools with the required level of data protection.

With a focus on the prioritization of workload protection, {{site.data.keyword.cloud_notm}} includes the following core features that you can leverage at rest and in transit for inbound and outbound traffic.

### Data at rest
{: #data-at-rest}

Key management, using {{site.data.keyword.keymanagementserviceshort}} and {{site.data.keyword.hscrypto}}, supports large key sizes that are considered quantum safe for data encryption (Data Encryption Key) and envelope encryption (Key Encryption Key). For more details, see [Protecting data with envelope encryption](/docs/key-protect?topic=key-protect-envelope-encryption) and [Bringing your encryption keys to the cloud](/docs/hs-crypto?topic=hs-crypto-importing-keys).

### Data in transit
{: #data-in-transit}

{{site.data.keyword.keymanagementserviceshort}} supports quantum safe enabled TLS connections through a hybrid method that combines Quantum Safe Cryptography and current ECC algorithms. {{site.data.keyword.keymanagementserviceshort}} uses the [Kyber algorithm](https://pq-crystals.org/kyber/index.shtml){: external} with NIST evaluation round three parameters. See [Introduction to Quantum-safe Cryptography in TLS](/docs/key-protect?topic=key-protect-quantum-safe-cryptography-tls-introduction) for more details.

Secure your outbound data with post-quantum support on {{site.data.keyword.cis_full_notm}}. See [Bringing post-quantum cryptography to IBM's edge](https://community.ibm.com/community/user/blogs/kevin-schroeder/2024/07/24/ibm-edge-post-quantum){: external} for more details.

For cloud native apps, TLS connections are quantum safe enabled with a custom ingress controller for {{site.data.keyword.cloud_notm}} {{site.data.keyword.containershort_notm}} and a custom router for {{site.data.keyword.openshiftlong_notm}}.

### Authentication
{: #data-auth}

A high-security version of round 2 Dilithium digital signatures in {{site.data.keyword.hscrypto}} is primarily used for data integrity, authenticity, and non-repudiation. See [Post-quantum cryptography support](/docs/hs-crypto?topic=hs-crypto-what-new#hs-crypto-8june2022) for more details.
