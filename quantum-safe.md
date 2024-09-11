---

copyright:
  years: 2024
lastupdated: "2024-09-11"

keywords: quantum safe, quantum computing, data encryption, key encryption, data at rest, data in transit, cryptography

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Quantum safe data protection
{: #quantum-safe}

Quantum computing promises to solve complex problems that even the most powerful computers can't solve today. At the same time, there is risk that data protected by public key cryptosystems could be recorded today and decrypted years later by using a Cryptographically Relevant Quantum Computer (CRQC). The {{site.data.keyword.cloud}} platform provides a secure, reliable, and cost-effective cloud computing environment that's tailored to your specific business needs. With security at the core, {{site.data.keyword.cloud_notm}} offers capabilities that you can use to integrate your apps and tools with the required level of data protection.
{: shortdesc}

With a focus on the prioritization of workload protection, {{site.data.keyword.cloud_notm}} includes the following core features that you can leverage at rest and in transit for inbound and outbound traffic.

## Data at rest
{: #at-rest}

Key management, using {{site.data.keyword.keymanagementserviceshort}} and {{site.data.keyword.hscrypto}}, supports large key sizes that are considered quantum safe for data encryption (Data Encryption Key) and envelope encryption (Key Encryption Key). For more details, see [Protecting data with envelope encryption](/docs/key-protect?topic=key-protect-envelope-encryption) and [Bringing your encryption keys to the cloud](/docs/hs-crypto?topic=hs-crypto-importing-keys).

## Data in transit
{: #in-transit}

{{site.data.keyword.keymanagementserviceshort}} supports quantum safe enabled TLS connections through a hybrid method that combines Quantum Safe Cryptography and current ECC algorithms. {{site.data.keyword.keymanagementserviceshort}} uses the [Kyber algorithm](https://pq-crystals.org/kyber/index.shtml){: external} with NIST evaluation round three parameters. See [Introduction to Quantum-safe Cryptography in TLS](/docs/key-protect?topic=key-protect-quantum-safe-cryptography-tls-introduction) for more details.

Secure your outbound data with post-quantum support on {{site.data.keyword.cis_full_notm}}. See [Bringing post-quantum cryptography to IBM's edge](https://community.ibm.com/community/user/cloud/blogs/kevin-schroeder/2024/07/24/ibm-edge-post-quantum){: external} for more details. 

For cloud native apps, TLS connections are quantum safe enabled with a custom ingress controller for {{site.data.keyword.cloud_notm}} {{site.data.keyword.containershort_notm}} and a custom router for {{site.data.keyword.openshiftlong_notm}}. See [Protecting apps on {{site.data.keyword.cloud_notm}} with Quantum Safe Cryptography](https://www.ibm.com/blog/protecting-apps-on-ibm-cloud-with-quantum-safe-cryptography/){: external} for more details. 

## Authentication
{: #auth}

A high-security version of round 2 Dilithium digital signatures in {{site.data.keyword.hscrypto}} is primarily used for data integrity, authenticity, and non-repudiation. See [Post-quantum cryptography support](/docs/hs-crypto?topic=hs-crypto-what-new#hs-crypto-8june2022) for more details. 
