---

copyright:
  years: 2021, 2024
lastupdated: "2024-05-25"

keywords: service endpoints, private endpoints, cloud service endpoints, vpe, cse, virtual private endpoint, platform endpoint, endpoints

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Public and private endpoints
{: #endpoints}



Cloud service endpoints (CSEs) and virtual private endpoints (VPEs) for {{site.data.keyword.vpc_full}} are private endpoint options available depending on the platform or catalog service that you are using. You can review a full list of the services that support private endpoint connections here.
{: shortdesc}

For a list of endpoints specific to the service you're using, go to the API docs for that service and review the Endpoint URLs section.
{: tip}

## Support for platform service endpoints
{: #support-platform-service-endpoints}

Review the [endpoints](#x2026820){: term} that you can use to connect programmatically with certain {{site.data.keyword.cloud}} platform services, such as billing and usage, catalogs, global search and tagging, and Identity and Access Management (IAM).

### Connectivity options
{: #endpoints-platform}

To interact with the platform APIs, you can use public endpoints or private endpoints.

* Public endpoints: You can connect to resources in all regions in your account over the {{site.data.keyword.cloud_notm}} public network.
* Private endpoints: After you enable [virtual routing and forwarding (VRF) and service endpoints](/docs/account?topic=account-vrf-service-endpoint) for your account, you can connect by using a private IP address that's accessible only through the {{site.data.keyword.cloud_notm}} private network.

### Billing and usage
{: #endpoints-billing-usage}

Platform APIs related to billing and usage include Enterprise Billing Units, Enterprise Usage Reports, Usage Metering, and Usage Reports. Review the tables in the following sections to determine the endpoints to use when you connect to these APIs.

#### Enterprise Billing Units
{: #endpoints-ent-billing}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 1. Public endpoint for Enterprise Billing Units API" caption-side="top"}
{: #public-ent-billing}
{: tab-title="Public"}
{: tab-group="ent-billing-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.billing.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 1. Private endpoints for Enterprise Billing Units API" caption-side="top"}
{: #private-ent-billing}
{: tab-title="Private"}
{: tab-group="ent-billing-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Enterprise Management
{: #endpoints-ent-management}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `enterprise.test.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 2. Public endpoint for Enterprise Management API" caption-side="top"}
{: #public-ent-management}
{: tab-title="Public"}
{: tab-group="ent-management-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.enterprise.test.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.enterprise.test.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 2. Private endpoints for Enterprise Management API" caption-side="top"}
{: #private-ent-management}
{: tab-title="Private"}
{: tab-group="ent-management-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Enterprise Usage Reports
{: #endpoints-ent-usage}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `enterprise.cloud.ibm.com/v1/resource-usage-reports` | HTTPS |
{: row-headers}
{: caption="Table 3. Public endpoint for Enterprise Usage Reports API (Beta)" caption-side="top"}
{: #public-ent-usage}
{: tab-title="Public"}
{: tab-group="ent-usage-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.enterprise.cloud.ibm.com/v1/resource-usage-reports` | HTTPS |
| Washington DC | `private.us-east.enterprise.cloud.ibm.com/v1/resource-usage-reports` | HTTPS |
{: row-headers}
{: caption="Table 3. Private endpoints for Enterprise Usage Reports API (Beta)" caption-side="top"}
{: #private-ent-usage}
{: tab-title="Private"}
{: tab-group="ent-usage-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Usage Metering
{: #endpoints-usage-meter}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 4. Public endpoint for Usage Metering API" caption-side="top"}
{: #public-usage-meter}
{: tab-title="Public"}
{: tab-group="usage-meter-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.billing.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 4. Private endpoints for Usage Metering API" caption-side="top"}
{: #private-usage-meter}
{: tab-title="Private"}
{: tab-group="usage-meter-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Usage Reports
{: #endpoints-usage-reports}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 5. Public endpoint for Usage Reports API" caption-side="top"}
{: #public-usage-reports}
{: tab-title="Public"}
{: tab-group="usage-reports-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.billing.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.billing.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 5. Private endpoints for Usage Reports API" caption-side="top"}
{: #private-usage-reports}
{: tab-title="Private"}
{: tab-group="usage-reports-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

### Catalogs
{: #endpoints-catalogs}

Platform APIs related to catalogs include Catalog Management and Global Catalog. Review the tables in the following sections to determine the endpoints to use when you connect to these APIs.

#### Catalog Management
{: #endpoints-catalog-mgmt}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `cm.globalcatalog.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 6. Public endpoint for Catalog Management API" caption-side="top"}
{: #public-catalog-mgmt}
{: tab-title="Public"}
{: tab-group="catalog-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.cm.globalcatalog.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.cm.globalcatalog.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 6. Private endpoints for Catalog Management API" caption-side="top"}
{: #private-catalog-mgmt}
{: tab-title="Private"}
{: tab-group="catalog-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Global Catalog
{: #endpoints-gc}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `globalcatalog.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 7. Public endpoint for Global Catalog API" caption-side="top"}
{: #public-catalog-gc}
{: tab-title="Public"}
{: tab-group="catalog-gc-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.globalcatalog.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.globalcatalog.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 7. Private endpoints for Global Catalog API" caption-side="top"}
{: #private-catalog-gc}
{: tab-title="Private"}
{: tab-group="catalog-gc-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

### Global search and tagging
{: #endpoints-search-tag}

The related platform APIs include Global Search and Global Tagging. Review the tables in the following sections to determine the endpoints to use when you connect to these APIs.

#### Global Search
{: #endpoints-search}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `api.global-search-tagging.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 8. Public endpoint for Global Search API" caption-side="top"}
{: #public-search}
{: tab-title="Public"}
{: tab-group="search-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `api.private.global-search-tagging.cloud.ibm.com` | HTTPS |
| Dallas | `api.private.us-south.global-search-tagging.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 8. Private endpoints for Global Search API" caption-side="top"}
{: #private-search}
{: tab-title="Private"}
{: tab-group="search-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Global Tagging
{: #endpoints-tagging}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `tags.global-search-tagging.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 9. Public endpoint for Global Tagging API" caption-side="top"}
{: #public-tagging}
{: tab-title="Public"}
{: tab-group="tagging-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `tags.private.global-search-tagging.cloud.ibm.com` | HTTPS |
| Dallas | `tags.private.us-south.global-search-tagging.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 9. Private endpoints for Global Tagging API" caption-side="top"}
{: #private-tagging}
{: tab-title="Private"}
{: tab-group="tagging-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

### IAM
{: #endpoints-iam}

Platform APIs related to IAM include IAM Access Groups, IAM Identity Services, and IAM Policy Management. Review the tables in the following sections to determine the endpoints to use when you connect to these APIs.

#### IAM Access Groups
{: #endpoints-accessgroups}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `iam.cloud.ibm.com/v2` | HTTPS |
{: row-headers}
{: caption="Table 10. Public endpoint for IAM Access Groups API" caption-side="top"}
{: #public-accessgroups}
{: tab-title="Public"}
{: tab-group="access-group-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `private.iam.cloud.ibm.com/v2` | HTTPS |
| Dallas | `private.us-south.iam.cloud.ibm.com/v2` | HTTPS |
| Washington DC | `private.us-east.iam.cloud.ibm.com/v2` | HTTPS |
{: row-headers}
{: caption="Table 10. Private endpoints for IAM Access Groups API" caption-side="top"}
{: #private-accessgroups}
{: tab-title="Private"}
{: tab-group="access-group-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### IAM Identity Services
{: #endpoints-IDservices}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `iam.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 11. Public endpoint for IAM Identity Services API" caption-side="top"}
{: #public-idservices}
{: tab-title="Public"}
{: tab-group="id-services-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `private.iam.cloud.ibm.com` | HTTPS |
| Dallas | `private.us-south.iam.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.iam.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 11. Private endpoints for IAM Identity Services API" caption-side="top"}
{: #private-idservices}
{: tab-title="Private"}
{: tab-group="id-services-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### IAM Policy Management
{: #endpoints-policymgmt}

See the following table to review the endpoints to use when you connect to the IAM Policy Management API.

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `iam.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 12. Public endpoint for IAM Policy Management API" caption-side="top"}
{: #public-policymgmt}
{: tab-title="Public"}
{: tab-group="policy-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `private.iam.cloud.ibm.com` | HTTPS |
| Dallas | `private.us-south.iam.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.iam.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 12. Private endpoints for IAM Policy Management API" caption-side="top"}
{: #private-policymgmt}
{: tab-title="Private"}
{: tab-group="policy-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### User Management
{: #endpoints-usermgmt}

See the following table to review the endpoints to use when you connect to the User Management API.

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `user-management.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 13. Public endpoint for User Management API" caption-side="top"}
{: #public-usermgmt}
{: tab-title="Public"}
{: tab-group="user-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.user-management.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.user-management.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 13. Private endpoints for User Management API" caption-side="top"}
{: #private-usermgmt}
{: tab-title="Private"}
{: tab-group="user-mgmt-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}


### Resource controller
{: #endpoints-rc}

Platform APIs related to resource controller include IBM Cloud Open Service Broker, Resource Controller V2, and Resource Manager V2. Review the tables in the following sections to determine the endpoints to use when you connect to these APIs.

#### IBM Cloud Open Service Broker
{: #endpoints-osb}

See the following table to review the endpoints to use when you connect to the IBM Cloud Open Service Broker API.

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global |  | HTTPS |
{: row-headers}
{: caption="Table 14. Public endpoint for IBM Cloud Open Service Broker API" caption-side="top"}
{: #public-osb}
{: tab-title="Public"}
{: tab-group="osb-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas |  | HTTPS |
| Washington DC |  | HTTPS |
{: row-headers}
{: caption="Table 14. Private endpoints for IBM Cloud Open Service Broker API" caption-side="top"}
{: #private-osb}
{: tab-title="Private"}
{: tab-group="osb-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Resource Controller V2
{: #endpoints-rcv2}

See the following table to review the endpoints to use when you connect to the Resource Controller V2 API.

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `resource-controller.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 15. Public endpoint for Resource Controller V2 API" caption-side="top"}
{: #public-rc}
{: tab-title="Public"}
{: tab-group="rc-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas |  | HTTPS |
| Washington DC |  | HTTPS |
{: row-headers}
{: caption="Table 15. Private endpoints for Resource Controller V2 API" caption-side="top"}
{: #private-rc}
{: tab-title="Private"}
{: tab-group="rc-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

#### Resource Manager V2
{: #endpoints-resourcemgrv2}

See the following table to review the endpoints to use when you connect to the Resource Manager V2 API.

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Global | `resource-controller.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 16. Public endpoint for Resource Manager V2 API" caption-side="top"}
{: #public-resourcemgr}
{: tab-title="Public"}
{: tab-group="resourcemgr-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

| Region | Endpoint | Protocol |
| ----- | ----- | ----- |
| Dallas | `private.us-south.resource-controller.cloud.ibm.com` | HTTPS |
| Washington DC | `private.us-east.resource-controller.cloud.ibm.com` | HTTPS |
{: row-headers}
{: caption="Table 16. Private endpoints for Resource Manager V2 API" caption-side="top"}
{: #private-resourcemgr}
{: tab-title="Private"}
{: tab-group="resourcemgr-endpoints"}
{: class="simple-tab-table"}
{: summary="Use the tab buttons to change the context of the table. This table has row and column headers. The row headers provide the endpoint value and the column headers identify the specific information available about the endpoints."}

Currently, not all services support the use service endpoints to connect over a private network. Review the following table for a list of services that support this feature. And, for specific use of service endpoints per service, refer to the documentation for that service.



## Service Endpoint Support
{: #service-endpoint-supported-table}

| Service | Supported |
|-----|-----|
| API Connect |  |
| API Gateway |  |
| Activity Tracker |  |
| Alert Notification |  |
| Analytics Engine |  |
| AnonTech ViziVault Platform |  |
| Anycloud Backup for 365 |  |
| Apache Spark |  |
| App Configuration | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| App Connect |  |
| App ID |  |
| Auto Scale for VPC |  |
| BUS4i System Copy - Migrate 23 for Power i |  |
| Bare Metal Server for VPC |  |
| Bespoken Automated Testing For IVR and Chat |  |
| Block Storage Snapshots for VPC |  |
| Block Storage for VPC |  |
| Blockchain |  |
| Blockchain Platform |  |
| Caveonix RiskForesight |  |
| Client VPN for VPC |  |
| Climate Impact API |  |
| Cloud Foundry Enterprise Environment |  |
| Cloud Native Storage and Data Service |  |
| Cloud Object Storage |  |
| Cloud for Education |  |
| Cloudant |  |
| Code Engine |  |
| Compliance and Customer Experience Automation |  |
| Compose Enterprise |  |
| Compose for Elasticsearch |  |
| Compose for JanusGraph |  |
| Compose for MongoDB |  |
| Compose for MySQL |  |
| Compose for PostgreSQL |  |
| Compose for RabbitMQ |  |
| Compose for Redis |  |
| Compose for RethinkDB |  |
| Compose for ScyllaDB |  |
| Compose for etcd |  |
| Container Registry |  |
| Continuous Delivery |  |
| Converlistics |  |
| Cost and Asset Management |  |
| CrushBank |  |
| Custom Migrations and Disaster Recovery as a Service |  |
| CyberStrong by CyberSaint |  |
| DNS Services |  |
| Data Engine (previously SQL Query) |  |
| Data Replication |  |
| Data Store for Memcache |  |
| DataStage |  |
| Databases for Cassandra | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for DataStax | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for EDB | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for Elasticsearch | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for EnterpriseDB | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for MongoDB | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for MySQL | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for PostgreSQL | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for Redis | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Databases for etcd | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Db2 |  |
| Db2 Warehouse |  |
| Dedicated Host for VPC |  |
| Direct Link Connect |  |
| Direct Link Dedicated |  |
| Dizzion Complete |  |
| Dizzion DaaS - Financial Services |  |
| Dizzion Flex |  |
| Dizzion Managed |  |
| Driver Behavior |  |
| Dubber Unified Recording |  |
| Email Surveillance |  |
| Event Management |  |
| Event Notifications | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Event Streams | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| F5 BIG-IP |  |
| FNTS Managed Services for PowerVS Cloud |  |
| FalconStor StorSafe VTL for Power On-Premises |  |
| File Storage for VPC |  |
| Floating IP for VPC |  |
| Flow Logs for VPC |  |
| FortiGate Security Appliance |  |
| FortiGate Virtual Appliance |  |
| Functions |  |
| Globalization Pipeline |  |
| HCX |  |
| HDM VMware Workload Analyzer |  |
| HDM VMware Workload Migrator |  |
| HPCaaS from Rescale |  |
| Historical Instrument Analytics |  |
| Horizon 7 |  |
| Human Intelligence |  |
| HyTrust CloudControl |  |
| HyTrust DataControl |  |
| HyTrust KeyControl |  |
| Hyper Protect Crypto Services |  |
| Hyper Protect Virtual Server for Classic |  |
| IBM Cloud Activity Tracker |  |
| IBM Cloud Backup for VPC |  |
| IBM Cloud Expert Services |  |
| IBM Cloud Monitoring |  |
| IBM Cloud Pak for Data |  |
| IBM Cloud Platform Group |  |
| IBM Cloud Platform OSB |  |
| IBM Cloud Private Hosted |  |
| IBM Cloud Reservations for VPC |  |
| IBM Cloud Secure Virtualization |  |
| IBM Cloud for VMware Mission Critical Workloads |  |
| IBM Cognos Dashboard Embedded |  |
| IBM Identity Mixer |  |
| IBM Knowledge Catalog |  |
| IBM Log Analysis |  |
| IBM Match 360 with Watson |  |
| IBM Spectrum Protect Plus |  |
| IBM Verify |  |
| IBM watsonx Code Assistant |  |
| Image Service for VPC |  |
| Informix |  |
| Instance Metadata for VPC |  |
| Instrument Analytics |  |
| Internet Services |  |
| Internet of Things Platform |  |
| Internet of Things Workbench |  |
| Investment Portfolio |  |
| KMIP for VMware |  |
| Key Protect | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Knowledge Studio |  |
| Komprise Elastic Data Migration |  |
| Komprise Intelligent Data Management Suite |  |
| Kubernetes Service | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Language Translator |  |
| Load Balancer for VPC |  |
| MQ |  |
| Managed Backup Services |  |
| Managed Disaster Recovery Services |  |
| Managed VMware Services |  |
| Messages for RabbitMQ | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| MinIO |  |
| Monitoring |  |
| Multi Volume Snapshots for VPC |  |
| Natural Language Understanding |  |
| NetApp ONTAP Select |  |
| Netezza Performance Server |  |
| Network ACL |  |
| NeuralSeek |  |
| OpenPages |  |
| PX-Backup for Kubernetes |  |
| Partner with Technology Expert Labs |  |
| Personality Insights |  |
| Placement Groups for VPC |  |
| Planning Analytics |  |
| Portfolio Optimization |  |
| Portworx Enterprise |  |
| PowerAI |  |
| PowerVS Migration as a Service |  |
| Predictive Market Scenarios |  |
| Product Insights - Log Management |  |
| ProtectIO DRaaS DIY |  |
| ProtectIO DRaaS Managed Service |  |
| Public Gateway |  |
| Qiskit Runtime |  |
| Raxak Protect |  |
| Real-Time Payments |  |
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Runbook Automation |  |
| SSH Key for VPC |  |
| Satellite |  |
| Satellite Infrastructure Service |  |
| Schematics |  |
| Secrets Manager | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Secure Automated Backup with Compass |  |
| Secure Gateway |  |
| Security Group for VPC |  |
| Security and Compliance Center | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Security and Compliance Center Workload Protection |  |
| SimpleCloud |  |
| Simulated Historical Instrument Analytics |  |
| Simulated Instrument Analytics |  |
| Single-node Trial for Data Protection and Disaster Recovery |  |
| Single-node Trial for Migration and App Modernization |  |
| Skytap On IBM Cloud |  |
| Software Instance |  |
| Speech to Text |  |
| Stocks and Crypto Intelligence |  |
| Streaming Analytics |  |
| Subnet |  |
| Text to Speech |  |
| Toolchain |  |
| Trade Surveillance |  |
| Transit Gateway |  |
| VCF as a Service - Cloud Director Site |  |
| VCF as a Service - Virtual Data Center |  |
| VMware Cloud Migration Services |  |
| VMware Solutions |  |
| VMware vCenter Server |  |
| VMware vSphere |  |
| VPC COaaS (VPC Cost Optimization as a Service) |  |
| VPC+ Cloud Migration |  |
| VPC+ DRaaS (VPC+ Disaster Recovery as a Service) |  |
| VPN for VPC |  |
| Veeam |  |
| Virtual Network Interface for VPC |  |
| Virtual Private Cloud |  |
| Virtual Private Endpoint for VPC |  |
| Virtual Private Network (VPN) |  |
| Virtual Server for VPC |  |
| Visual Recognition |  |
| Voice Agent with Watson |  |
| Watson Discovery | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Watson Machine Learning | ![Checkmark icon](../../icons/checkmark-icon.svg) |
| Watson Query |  |
| Watson Studio |  |
| Weather Company Data |  |
| WebSphere Application Server |  |
| Workload Scheduler |  |
| Workspace for Power Virtual Server |  |
| Zerto |  |
| etiCloud secure digital agile workplace |  |
| vRealize Operations and Log Insight |  |
| watsonx |  |
| watsonx Assistant |  |
| watsonx.data |  |
| watsonx.governance |  |
{: row-headers}
{: class="comparison-table"}
{: caption="Services that support the use of service endpoints" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify the service. The column header identifies support for the service endpoint feature. Each cell in the table that has a checkmark means the service identified in that row supports using service endpoints."}


## VPE endpoint support
{: #vpe-endpoing-support}

Future VPE list of services dynamic table to be inserted