---

copyright:
  years: 2021, 2024
lastupdated: "2026-05-18"

keywords: encrypt ibm cloud data, byok, kyok, customer managed keys, byok, kyok, key encryption, data encryption, keep your own key, bring your own key, encryption at rest, encryption in transit, data at rest, data in transit

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


# Encrypting data in IBM Cloud with your own keys
{: #key-encryption}

Learn how to secure IBM Cloud data at REST and in transit using BYOK and KYOK encryption options for enhanced security and control.
{: shortdesc}

IBM Cloud&reg; encrypts all data in transit and at rest. Additionally, you can configure IBM Cloud services to encrypt your data at rest with your own keys, and then monitor the events around the lifecycle of the encryption keys with IBM Cloud&reg; Activity Tracker.

IBM Cloud supports multiple encryption options, whether you're looking for a solution that supports the bring your own key (BYOK) or keep your own key (KYOK) functionality. For an in-depth look at the options to secure your data depending on your organization's needs, see [Data security](https://www.ibm.com/think/topics/data-security){: external}.

## Bring your own keys
{: #byok-overview}

Many IBM Cloud services support data encryption by using customer-managed keys, also known as bring your own key (BYOK). The most common use case for BYOK is using IBM&reg; Key Protect to [bring your encryption keys to the cloud](/docs/key-protect?topic=key-protect-importing-keys). Key Protect is a multi-tenant service using FIPS 140-2 Level 3 HSM. For a list of services that can be integrated with Key Protect, see [Integrating services](/docs/key-protect?topic=key-protect-integrate-services).

## Keep your own keys
{: #kyok-overview}

IBM Cloud also provides IBM Cloud Hyper Protect Crypto Services, which is a dedicated key management service and hardware security module (HSM). Hyper Protect Crypto Services features keep your own key (KYOK) encryption capabilities backed by FIPS 140-2 Level 4 certification. With this option, it makes the IBM public cloud the industry's most secure and open public cloud for business. For a list of services that can be integrated with Hyper Protect Crypto Services, see [Integrating IBM Cloud services with Hyper Protect Crypto Services](/docs/hs-crypto?topic=hs-crypto-integrate-services).

## Auditing the lifecycle of your keys
{: #key-auditing}

You can use Activity Tracker to monitor the activity of your keys. The Activity Tracker service provides the framework and functions to monitor API calls to services on IBM Cloud and produces the evidence to comply with corporate policies and market industry-specific regulations. Events that are tracked by Activity Tracker are either global or regional, and global events, such as provisioning a service, are available through the global domain instance that is located in Frankfurt. Events that are generated by an instance of Key Protect or Hyper Protect Crypto Services are automatically forwarded to the IBM Cloud instance that is available in the same location.

See [Provisioning an instance](/docs/cloud-logs?topic=cloud-logs-atla) to configure your monitoring instance. Whether you're using Key Protect or Hyper Protect Crypto Services, you can track events like creating a key, deleting a key, rotating a key, and more:

* [IBM Cloud Activity Tracker events for Key Protect](/docs/key-protect?topic=key-protect-at-events)
* [IBM Cloud Activity Tracker events for Hyper Protect Crypto Services](/docs/hs-crypto?topic=hs-crypto-at-events)
