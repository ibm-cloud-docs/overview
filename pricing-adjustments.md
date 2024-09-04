---


copyright:
  years: 2023, 2024
lastupdated: "2024-09-04"

published-location: https://cloud.ibm.com/docs/overview?topic=overview-price-adjustments

keywords:

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# {{site.data.keyword.cloud_notm}} price changes
{: #price-adjustments}

The following page outlines the price changes for {{site.data.keyword.cloud}}.
{: shortdesc}

## January 2025 price changes
{: #jan-2025}

Effective 1 January 2025, {{site.data.keyword.cloud_notm}} is making price changes for infrastructure as a service (IaaS) and platform as a service (PaaS) services, {{site.data.keyword.cos_full_notm}}, R1Soft Backup Service, {{site.data.keyword.sysdigsecure_full_notm}} cloud security posture management, and {{site.data.keyword.keymanagementservicelong_notm}}. See the following sections for additional details.

### Premium changes by location for IaaS
{: #iaas-adjustments-jan-2025}

Location premiums for most non-US multizone regions (MZRs) will remain unchanged. The premium for Sao Paulo (`br-sao`) will increase by 3 percentage points.

| MZR locations| Data centers |Current location premium | New location premium | Effective increase |
|-------|------|-------|-------|-------|
| Dallas (`us-south`)| DAL10, DAL12, DAL13, DAL14 | 0% | 0% | No increase |
| Washington DC (`us-east`) | WDC04, WDC06, WDC07 | 0% | 0% | No increase |
| Toronto (`ca-tor`) | TOR01, TOR04, TOR05 |6% | 6% | No increase |
| London (`eu-gb`) | LON04, LON05, LON06 | 13% | 13% | No increase |
| Frankfurt (`eu-de`) | FRA02, FRA04, FRA05 | 16% | 16% | No increase |
| Madrid (`eu-es`) | MAD02, MAD04, MAD05 | 16% | 16% | No increase |
| Tokyo (`jp-tok`) | TOK02, TOK04, TOK05 | 20% | 20% | No increase |
| Sydney (`au-syd`) | SYD01, SYD04, SYD05 | 20% | 20% | No increase |
| Sao Paulo (`br-sao`) | SAO01, SAO04, SAO05 | 29% | 32% | 2.3% |
{: caption="Table 1. IaaS MZR location premium changes" caption-side="top"}


Location premiums for classic data centers will increase as follows:

| Classic data centers | Current location premium | New location premium | Effective increase |
|-------|-------|-------|-------|
| DAL08 | 11% | 11% | No increase |
| DAL09 | 0% | 6% | 6.0% |
| SJC03 | 0% | 6% | 6.0% |
| SJC04 | 0% | 6% | 6.0% |
| WDC03 | 11% | 11% | No increase |
| AMS03 | 6% | 13% | 6.6% |
| MON01 | 6% | 13% | 6.6% |
| LON02 | 13% | 20% | 6.2% |
| MIL01 | 16% | 22% | 5.2% |
| PAR01 | 16% | 22% | 5.2% |
| CHE01 | 20% | 20% | No increase |
| SNG01 | 20% | 20% | No increase |
{: caption="Table 2. Classic data center location premium changes" caption-side="top"}

Existing VMware, {{site.data.keyword.powerSys_notm}} (including SAP on {{site.data.keyword.powerSys_notm}}), High Performance Computing, and SAP deployments made before 1 January 2025 will be exempt from these increases and prices will remain unchanged.
{: note}


### Premium changes by location for PaaS services
{: #paas-adjustments-jan-2025}

PaaS services will adopt the same location premiums as IaaS services shown in the previous section.

**Excluded** from this change are the following services:
- {{site.data.keyword.containerlong_notm}} and {{site.data.keyword.openshiftlong_notm}}
- {{site.data.keyword.logs_full_notm}}
- {{site.data.keyword.cloudaccesstraillong_notm}} (deprecated)
- {{site.data.keyword.loganalysislong_notm}} (deprecated)
- {{site.data.keyword.monitoringlong_notm}}
- {{site.data.keyword.databases-for-elasticsearch_full_notm}}
- {{site.data.keyword.databases-for-enterprisedb_full_notm}}
- {{site.data.keyword.databases-for-etcd_full_notm}}
- {{site.data.keyword.databases-for-mongodb_full_notm}}
- {{site.data.keyword.databases-for-mysql_fullnotm}}
- {{site.data.keyword.databases-for-postgresql_full_notm}}
- {{site.data.keyword.databases-for-redis_full_notm}}
- {{site.data.keyword.messages-for-rabbitmq_full_notm}}

**Included** in this change are the following services:
- {{site.data.keyword.appconfig_full}}
- {{site.data.keyword.appid_full_notm}}
- {{site.data.keyword.cloudant_short_notm}}
- {{site.data.keyword.codeenginefull_notm}}
- {{site.data.keyword.registrylong_notm}}
- {{site.data.keyword.cloud_notm}} Continuous Delivery
- {{site.data.keyword.en_full_notm}}
- {{site.data.keyword.satellitelong_notm}}
- {{site.data.keyword.keymanagementservicelong_notm}}
- IBM Event Streams for {{site.data.keyword.cloud_notm}}
- {{site.data.keyword.secrets-manager_full_notm}}
- {{site.data.keyword.compliance_long}}
- {{site.data.keyword.sysdigsecure_full_notm}}


### {{site.data.keyword.cos_full_notm}}
{: #cos-adjustments-jan-2025}

{{site.data.keyword.cos_short}} will introduce charges for Aspera high-speed uploads and adopt new, simpler, flat, and consistent charges for high-speed downloads:

| Transfer | Current charges | 2025 charges - EU/UK/US/Japan | 2025 charges - All other regions |
|--------|--------|--------|--------|
| High-speed uploads | $0.00 | 10 GB free/month \n 10 GB+ $0.04/GB/month | 10 GB free/month \n 10 GB+ $0.08/GB/month |
| High-speed downloads | 0-50 TB  $0.0836/GB \n Next 100 TB $0.0627/GB \n 150 TB+ $0.0418/GB | 10 GB free/month \n 10 GB+ $0.04/GB/month | 10 GB free/month \n 10 GB+ $0.08/GB/month |
{: caption="Table 3. New {{site.data.keyword.cos_short}} high-speed data transfer charges." caption-side="top"}

Additionally, {{site.data.keyword.cos_short}} prices will be increased by 2% in the Sao Paulo (`br-sao`) and Toronto (`ca-tor`) regions. In Chennai (`in-che`), the 2% increase will apply to Archive only.


### R1Soft Backup Services
{: #r1soft-adjustments-jan-2025}

Charges for R1Soft Backup Services will increase as follows:

| Tier | Current charges | 2025 charges |
|-----|-----|-----|
| 1 Pack | $7.50 | $10.00 |
| 5 Pack | $36.25 | $40.00 |
| 10 Pack | $67.50 | $75.00 |
| 25 Pack | $143.75 | $160.00 |
{: caption="Table 4. R1Soft backup services changes" caption-side="top"}


### {{site.data.keyword.compliance_long}}
{: #scc-adjustments-jan-2025}

Charges for {{site.data.keyword.sysdigsecure_full_notm}} cloud security posture management will increase from $8.24/compute instance/month to $18.00/compute instance/month.

Volume discounts are available as follows:

| Number of compute instances | Current price/month | 2025 price/month |
|--------------------|---------------------|------------------|
| 1 - 250 | $8.24 | $18.00 |
| 251 - 500 | $7.004 | $15.30 |
| 501 - 1000 | $6.18 | $13.50 |
| 1001 - 2500 | $5.768 | $12.60 |
| 2501 - 5000 | $4.944 | $10.80 |
| 5000+ | $4.523 | $9.90 |
{: caption="Table 5. {{site.data.keyword.sysdigsecure_full_notm}} cloud security posture management changes" caption-side="top"}

All other {{site.data.keyword.compliance_short}} charges remain unchanged.
{: note}


### {{site.data.keyword.keymanagementservicelong_notm}}
{: #keyprotect-adjustments-jan-2025}

{{site.data.keyword.keymanagementserviceshort}} is making two changes to its pricing structure:
1. The current free allocations of 5 key versions will be eliminated. The standard charge of $1.0764 /key version/month will apply to all keys.
2. Charges for the global resiliency feature will be $100.00/duplicate region/month plus $1.0764/month for each duplicated key.


## April 2024 price changes
{: #april-2024}

Effective 1 April 2024, {{site.data.keyword.cloud_notm}} is making the following price changes for cPanel and {{site.data.keyword.redhat_full}} Enterprise Linux.

### {{site.data.keyword.redhat_notm}} Enterprise Linux
{: #rhel-adjustments}

Effective 1 April 2024, {{site.data.keyword.redhat_notm}} is making changes to {{site.data.keyword.redhat_notm}} Enterprise Linux (RHEL) prices and introducing a new tier structure for virtual server instance pricing. {{site.data.keyword.cloud_notm}} is making the following price changes to reflect the {{site.data.keyword.redhat_notm}} changes.

#### RHEL on Bare Metal Servers
{: #rhel-bare-metal-servers}

For Bare Metal Servers, RHEL prices will change as follows:

| Platform | Offering | Current charges | New charges |
|------|----------|-----------------|-------------|
| VPC Bare Metal | RHEL and RHEL for SAP Applications Hourly | $0.120 | $0.132 |
| Classic Bare Metal | RHEL Monthly | $90.00 | $99.00 |
| Classic Bare Metal | RHEL for SAP Applications Monthly | $90.00 | $99.00 |
| Classic Bare Metal | RHEL for SAP with HA and US Monthly | $448.00 | $492.80 |
{: caption="Table 6. RHEL on Bare Metal Servers" caption-side="top"}

#### RHEL on Virtual Server Instances
{: #rhel-vsi}

{{site.data.keyword.redhat_notm}} prices for virtual server instances are changing from a 2-tier per server model to a 3-tier per vCPU model as follows:

| Old Model - charges based on server size | Size |
|----------|------|
| Small    | 1-4 vCPUs |
| Large    | 5+ vCPUs |
{: caption="Table 7. Charges based on server size" caption-side="top"}


| New model - charges per vCPU | Size |
|------------------------------|------|
| Small | 1-8 vCPUs |
| Mid | 9-127 vCPUs |
| Large | 128+ vCPUs |
{: caption="Table 8. Charges per vCPU" caption-side="top"}

With this new model, prices effective 1 April 2024 will be as follows:

| Platform | Offering | Current charges (per server) | New charges (per vCPU) |
|----------|----------|-----------------|-------------|
| Classic | VSI RHEL Hourly | Small: $0.06  \n Large: $0.12 | Small: $0.017  \n Mid: $0.011  \n Large: not offered |
| Classic | VSI RHEL Monthly | Small: $45.00  \n Large: $93.00 | Small: $12.584  \n Mid: $8.829  \n Large: not offered |
| VPC     | VSI RHEL for SAP Apps Hourly | Small: $0.06  \n Large: $0.12 | Small: $0.017  \n Mid: $0.011  \n Large: $0.009 |
| VPC     | VSI RHEL for SAP Apps for HA and US Hourly | Small: $0.14  \n Large: $0.31 | Small: $0.023  \n Mid: $0.016  \n Large: $0.015 |
| VPC     | VSI RHEL Hourly | Small: $0.06  \n Large: $0.12 | Small: $0.017  \n Mid: $0.011  \n Large: $0.009 |
| VMware Shared | VSI RHEL Hourly | Small: $0.06  \n Large: $0.12 | Small: $0.017  \n Mid: $0.011  \n Large: $0.009 |
| VMware-aaS | VSI RHEL Hourly | Small: $0.06  \n Large: $0.12 | Small: $0.017  \n Mid: $0.011  \n Large: $0.009 |
{: caption="Table 9. Comparison of pricing model changes" caption-side="top"}

### cPanel
{: #cpanel-adjustments}

Effective 1 April 2024, {{site.data.keyword.cloud_notm}} is making the following price changes for cPanel. These prices reflect a vendor price increase that was made in December 2023.

| cPanel Option | Current monthly charge | New charge from 1 April 2024 |
|-------|-------|-------|
| cPanel/WHM with Fantastico and RVskin Admin Cloud up to 5 Accounts | $14.00 | $30.25 |
| cPanel/WHM with Fantastico and RVskin Pro Cloud up to 30 Accounts |	$19.00 | $42.99 |
| cPanel/WHM with Fantastico and RVskin Plus Cloud up to 50 Accounts | $27.00 | $57.00 |
| cPanel/WHM with Fantastico and RVskin Premier Cloud up to 100 Accounts | $48.50 | $72.55 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Metal up to 100 Accounts | $48.50 | $72.55 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 150 Accounts | $63.50 | $81.80 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 200 Accounts | $78.50 | $100.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 250 Accounts | $93.50 | $120.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 300 Accounts | $108.50 | $140.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 350 Accounts | $123.50 | $160.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 400 Accounts | $138.50 | $180.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 450 Accounts | $153.50 | $200.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 500 Accounts | $168.50 | $220.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 550 Accounts | $183.50 | $240.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 600 Accounts | $198.50 | $260.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 650 Accounts | $213.50 | $280.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 700 Accounts | $228.50 | $300.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 750 Accounts | $243.50 | $320.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 800 Accounts | $258.50 | $340.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 850 Accounts | $273.50 | $360.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 900 Accounts | $288.50 | $380.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 950 Accounts | $303.50 | $400.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1000 Accounts | $318.50 | $420.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1050 Accounts | $333.50 | $440.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1100 Accounts | $348.50 | $460.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1150 Accounts | $363.50 | $480.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1200 Accounts | $378.50 | $500.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1250 Accounts | $393.50 | $520.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1300 Accounts | $408.50 | $540.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1350 Accounts | $423.50 | $560.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1400 Accounts | $438.50 | $580.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1450 Accounts | $453.50 | $600.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 1500 Accounts | $468.50 | $620.99 |
| cPanel/WHM with Fantastico/Softaculous and RVskin Premier Fixed Package up to 2000 Accounts | $618.50 | $820.99 |
{: caption="Table 10. cPanel pricing changes" caption-side="top"}

## January 2024 price changes
{: #jan-2024}

Effective 1 January 2024, {{site.data.keyword.cloud_notm}} is making the following price changes for IaaS and PaaS services.

### IaaS data center premium changes
{: #iaas-adjustments}

Prices for {{site.data.keyword.cloud_notm}} infrastructure services vary from location to location, based on a percentage premium from US base prices. Effective 1 January 2024, these location premiums are changing as follows:

| Location| Current premium | New premium | Effective increase |
|-------|-------|-------|-------|
| Dallas \n San Jose \n Washington DC | 0% | 0% | No Change |
| Amsterdam \n Montreal \n Toronto | 3% | 6% | +2.9% |
| London | 7% | 13% | +5.6% |
| Frankfurt \n Madrid \n Milan \n Paris | 10% | 16% | +5.5% |
| Osaka \n Singapore \n Tokyo | 13% | 20% | +6.2% |
| Chennai \n Sydney | 20% | 20% | No Change |
| Sao Paulo | 20% | 29% | +7.5% |
{: caption="Table 11. IaaS pricing changes" caption-side="top"}

These new premiums will apply to Bare Metal Servers, Virtual Server Instances, File and Block Storage, and Networking infrastructure, for both classic and VPC offerings.

For {{site.data.keyword.cos_full}}, the premiums that are mentioned in the previous table will affect the {{site.data.keyword.cos_short}} service only in the Sao Paulo (`br-sao`) region. Furthermore, there will be a global increase of 25% in **Accelerated Archive** prices and a 26% increase for **Deep Archive** storage.

There will be no changes to the existing premiums for {{site.data.keyword.powerSysFull}}, third-party software, or network bandwidth.

### PaaS global price changes
{: #paas-adjustments}

Effective 1 January 2024, all prices for {{site.data.keyword.cloud_notm}} service will increase by 3% globally. This increase covers:

- {{site.data.keyword.cloudaccesstraillong}}
- {{site.data.keyword.appid_full}}
- {{site.data.keyword.codeenginefull}}
- {{site.data.keyword.contdelivery_full}}
- {{site.data.keyword.sqlquery_full}}
- {{site.data.keyword.security_broker_full}}
- {{site.data.keyword.databases-for-cassandra_full}}
- {{site.data.keyword.databases-for-elasticsearch_full}}
- {{site.data.keyword.databases-for-enterprisedb_full}}
- {{site.data.keyword.databases-for-etcd_full}}
- {{site.data.keyword.databases-for-mongodb_full}}
- {{site.data.keyword.databases-for-mysql_full}}
- {{site.data.keyword.databases-for-postgresql_full}}
- {{site.data.keyword.databases-for-redis_full}}
- {{site.data.keyword.en_full}}
- {{site.data.keyword.cis_full}}
- {{site.data.keyword.containerlong}} and {{site.data.keyword.openshiftlong}}
- {{site.data.keyword.loganalysislong}}
- {{site.data.keyword.messages-for-rabbitmq_full}}
- {{site.data.keyword.monitoringlong}}
- {{site.data.keyword.satellitelong}}
- {{site.data.keyword.secrets-manager_full}}
- {{site.data.keyword.compliance_full}}
- {{site.data.keyword.sysdigsecure_full}}
- {{site.data.keyword.cloudantfull}}
- {{site.data.keyword.messagehub_full}}
- {{site.data.keyword.keymanagementservicefull}}
