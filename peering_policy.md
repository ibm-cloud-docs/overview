---

copyright:
  years: 2020, 2024
lastupdated: "2026-05-18"

keywords: ibm cloud peering, network peering, peeringdb, public peering

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


# IBM Cloud public peering policy and guidelines for network connection
{: #public-peering}

Review IBM Cloud's public peering policy, guidelines for network peering, peeringdb requirements, and operational standards for connecting with IBM Cloud securely and efficiently.
{: shortdesc}

Public peering is conducted across a shared network. Peering requests can be accepted when a mutually agreeable decision to peer based on operational needs exists.


## Guidelines and general information
{: #guide-gen-info}

The following are guidelines and some general information for public peering with IBM Cloud&reg;.

- Potential and current peers must have and maintain a valid [PeeringDB.com](https://www.peeringdb.com/){: external} record.
- Use of the [Internet Routing Registry (IRR)](https://irr.net/){: external} is required for prefix filtering.
- Peers must supply a contact with 24x7 availability, such as a Network Operations Center.
- Peers must not use any form of gateway of last resort or default route that is directed at IBM Cloud.
- Peers must provide access to a looking glass or traceroute server to facilitate troubleshooting.
- Peer announcements must be consistent across all Interconnect locations.
- IBM Cloud sends and accepts MED attributes by request only.

IBM Cloud reserves the right to suspend peering for an indefinite period if any form of network abuse is detected and verified to be taking place through the peering interconnect. This suspension includes setting a default route to IBM Cloud. IBM Cloud doesn't accept any IPv4 announcements smaller than /24 or IPv6 announcements smaller than /48. An MD5 password is preferred but not required.

For more information, see the [PeeringDB record](https://www.peeringdb.com/asn/36351){: external}.

If IBM Cloud's operational needs cause a peering arrangement to conflict with the best interest of IBM Cloud, IBM Cloud reserves the right to end the peering agreement with reasonable advance notice.
{: note}

## Public peer exchanges
{: #peer-exchanges}

The following table shows the current public peer exchanges.

| Country       | City        | State or Province | Exchange            |
|---------------|-------------|-------------------|---------------------|
| Brazil | São Paulo | São Paulo         | PTT-SP   |
| Canada       | Toronto     | Ontario          | TorIX               |
| United States | Denver     | Colorado        | ANY2 Denver         |
| United States | Denver     | Colorado        | IX Denver           |
| United States | Miami      | Florida          | FL-IX               |
| United States | Miami      | Florida          | Equinix Miami       |
| United States | Boston    | Massachusetts     | MASS-IX             |
| United States | New York  | New York        | DE-CIX NYC          |
| United States | New York  | New York        | TIE NYC             |
| United States | New York  | New York        | NYIIX               |
| United States | Seattle    | Washington      | SIX                 |
| United States | Los Angeles | California      | ANY2 Los Angeles    |
| United States | Los Angeles | California      | Equinix Los Angeles |
| United States | Palo Alto  | California       | Equinix Palo Alto   |
| United States | San Jose  | California      | Equinix San Jose    |
| United States | Atlanta    | Georgia          | TIE-ATL             |
| United States | Chicago    | Illinois        | Equinix Chicago     |
| United States | Dallas    | Texas            | Equinix Dallas      |
| United States | Dallas    | Texas            | DE-CIX DAL          |
| United States | Ashburn    | Virginia        | Equinix Ashburn     |
| United States | Ashburn    | Virginia        | LINX NoVa           |
{: class="simple-tab-table"}
{: caption="Public peer exchanges for North and South America" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #NA}
{: tab-title="Americas"}

| Country or region                | City            | State or Province  | Exchange          |
|-------------------------------|-----------------|--------------------|-------------------|
| Australia | Melbourne | Victoria               | Equinix Melbourne            |
| Australia | Melbourne | Victoria               | IX Australia Victoria        |
| Australia | Melbourne | Victoria              | MegaIX Melbourne             |
| Australia | Sydney  | New South Wales        | Equinix Sydney               |
| Australia | Sydney  | New South Wales        | IX Australia New South Wales |
| Australia | Sydney  | New South Wales        | MegaIX Sydney                |
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong S.A.R. of the PRC    | Equinix Hong Kong |
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong S.A.R. of the PRC    | HKIX              |
| Hong Kong S.A.R. of the PRC   | New Territories | Hong Kong          | BBIX Hong Kong    |
| India                        | Mumbai           | Mumbai             | AMS-IX Mumbai     |
| India                        | Mumbai           | Mumbai             | DE-CIX Mumbai     |
| India                        | Mumbai           | Mumbai             | Extreme-IX Mumbai |
| Japan                        | Osaka           | Japan             | BBIX Osaka       |
| Japan                         | Osaka           | Japan             | JPIX Osaka       |
| Japan                         | Osaka           | Japan             | JPNAP Osaka       |
| Japan                         | Tokyo           | Japan              | BBIX Tokyo        |
| Japan                         | Tokyo           | Japan              | Equinix Tokyo     |
| Japan                         | Tokyo           | Japan             | JPNAP Tokyo       |
| Singapore                     | Singapore       | Singapore          | BBIX Singapore    |
| Singapore                     | Singapore       | Singapore          | Equinix Singapore |
| Taiwan                        | Taipei          | Taipei             | TPIX-TW          |
{: class="simple-tab-table"}
{: caption="Public peer exchanges for Asia Pacific" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #AP}
{: tab-title="Asia Pacific"}

| Country     | City      | State or Province  | Exchange         |
|-------------|-----------|--------------------|------------------|
| Germany    | Frankfurt | Hesse             | DE-CIX           |
| Germany    | Frankfurt | Hesse              | NIX.CZ           |
| England    | London   | England            | LINX Juniper LAN |
| England    | London   | England            | LINX Extreme LAN |
| France    | Paris    | Île-de-France     | Equinix Paris    |
| Italy      | Milan    | Italy             | MIX-IT           |
| Netherlands | Amsterdam | North Holland      | AMS-IX           |
| Netherlands | Amsterdam | North Holland      | NL-IX            |
| Spain      | Madrid | Madrid | DE-CIX Madrid |
| Spain      | Madrid | Madrid | ESPANIX Madrid Lower LAN |
| Spain      | Madrid | Madrid | ESPANIX Madrid Upper LAN |
| Spain      | Madrid | Madrid | Equinix Madrid |
{: class="simple-tab-table"}
{: caption="Public peer exchanges for Europe" caption-side="top"}
{: tab-group="public-peer-exchanges"}
{: #EU}
{: tab-title="Europe"}
