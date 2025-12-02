---
copyright:
  years: 2015, 2025

lastupdated: "2025-12-02"

keywords: release notes, what's new in IBM Cloud, what's new for the platform, what is new, cloud updates, new features, platform release notes

subcollection: overview

content-type: release-note

---

{{site.data.keyword.attribute-definition-list}}

# Release notes for the {{site.data.keyword.cloud_notm}} platform
{: #whatsnew}

Stay up to date with what's new in {{site.data.keyword.Bluemix}} and the latest feature releases that are available on the platform so that you get the most out of your {{site.data.keyword.cloud_notm}} experience.
{: shortdesc}


## December 2025
{: #december-2025}

### 02 December 2025
{: #december-01-2025}

Updates to the basic support policy
:   To improve efficiency and align with industry standards, {{site.data.keyword.cloud_notm}} is updating the Basic Support policy starting 5 January 2026. These changes emphasize self-service and AI-driven support, reducing reliance on manual case handling for technical issues.

   Starting on that date, users with a basic support plan will no longer be able to open technical support cases through either the portal or API. Basic support will also no longer support the ability to initiate or escalate managed escalations through the portal or internal channels. 

   Users will still be able to self-report hard ware issues, submit account or billing requests - including quota increases - via the portal, respond to IBM-initiated support cases, and access the following self-service tools: {{site.data.keyword.cloud_notm}} AI assistant, {{site.data.keyword.cloud_notm}} docs, Community forums, and status pages.


## October 2025
{: #october-2025}

### 31 October 2025
{: #overview-oct3125}
{: release-notes}

Chennai single-campus MZR availability
:   A new single-campus MZR (SC-MZR) location is now available in Chennai (`in-che`). You can review the [Service and infrastructure availability by location](/docs/overview?topic=overview-services_region) page to learn about the services that are available in this new location. For more information about {{site.data.keyword.cloud_notm}} SC-MZRs and MZRs, see [{{site.data.keyword.cloud_notm}} region and data center locations for resource deployment](/docs/overview?topic=overview-locations).


## September 2025
{: #september-2025}

### 22 September 2025
{: #overview-september2225}
{: release-notes}

Carbon insights at the data center-level
:   Tracking carbon emissions at the data center-level helps you measure, analyze, and report the environment impact of your workloads with accuracy. By breaking down emissions at both the data center and regional levels, users gain deeper insights into where and how their workloads use energy. It enables more informed deployment decisions, better sustainability reporting, and improved alignment with global compliance standards. For more information, see [{{site.data.keyword.cloud_notm}} carbon calculator methodology](/docs/account?topic=account-what-is-cloud-calc&interface=ui#carbon-methodology).

## August 2025
{: #august-2025}

### 08 August 2025
{: #overview-august0825}
{: release-note}

Centralized IAM policy support for enterprise log routing
:   {{site.data.keyword.cloud_notm}} now supports centralized IAM policies for enterprise-wide log routing. This enhancement enables enterprise customers to configure a single service-to-service authorization policy that allows log forwarding from multiple child accounts to a centralized logging instance, without the need to create individual policies for each account. For more information, see [Setting up centralized access to manage enterprise audit logs](/docs/enterprise-management?topic=enterprise-management-enterprise-access-management#enterprise-audit-logs).

### 07 August 2025
{: #overview-august0725}
{: release-note}

Federate enterprise IdP administrators to {{site.data.keyword.cloud_notm}} by using SAML
:   {{site.data.keyword.cloud_notm}} now supports SAML-based identity federation directly through {{site.data.keyword.cloud_notm}} IAM, enabling customers to federate identities from their external Identity Providers (IdPs) to manage {{site.data.keyword.cloud_notm}} resources. This enhancement helps ensure continuity for existing {{site.data.keyword.appid_short}} integrations and provides a seamless path for onboarding to the new federation capability with minimal impact. For more information, see [Enabling authentication from an external identity provider](/docs/account?topic=account-ibm-idp-integration).

Stand-alone policy templates in IAM
:   IAM supports the creation of stand-alone policy templates. This capability enables enterprise administrators to define access rules independently, without linking them to an access group or trusted profile template. It centralizes policy management, reduces duplication, and simplifies applying consistent access rules across enterprise accounts. For more information, see [Creating a stand-alone policy template](/docs/enterprise-management?topic=enterprise-management-policy-template-create&interface=ui#create-standalone-policytemplate-ui).

## July 2025
{: #july-2025}

### 01 July 2025
{: #overview-july0125}
{: release-note}

Manage one-time view credentials
:   {{site.data.keyword.cloud_notm}} enables one-time view by default for newly created service credentials. This change enhances security by ensuring that credentials are only visible at the time of creation. For more information, see [Connecting service apps](/docs/account?topic=account-service_credentials&interface=ui).

## April 2025
{: #april-2025}

### 30 April 2025
{: #overview-apr1725}
{: release-note}

Experimental: Extend a deployable architecture as you onboard it to a private catalog
:   You can now create a more complex deployable architecture by stacking it with other architectures as you onboard it to a private catalog. By doing so, you can include dependencies and optional deployable architectures for extended use cases, so users can customize your solution to meet their needs. For more information, see [Extending a deployable architecture during onboarding](/docs/secure-enterprise?topic=secure-enterprise-extend-da).

## March 2025
{: #march-2025}

### 26 March 2025
{: #overview-mar2625}
{: release-note}

{{site.data.keyword.cloud_notm}} AI assistant can now assist you with getting support
:   To bring you an updated platform experience, the {{site.data.keyword.cloud_notm}} AI assistant is available to help with your questions about {{site.data.keyword.cloud_notm}} and can assist you with getting support for account, billing, and technical support issues according to your support plan. You can query about your support cases or request to be handed off to a live support agent. For more information, see [Getting help from the AI assistant](/docs/overview?topic=overview-ask-ai-assistant).

### 13 March 2025
{: #overview-mar1325}
{: release-note}

Montreal single-campus MZR availability
:   A new single-campus MZR (SC-MZR) location is now available in Montreal (`ca-mon`). You can review the [Service and infrastructure availability by location](/docs/overview?topic=overview-services_region) page to learn about the services that are available in this new location. For more information about {{site.data.keyword.cloud_notm}} SC-MZRs and MZRs, see [{{site.data.keyword.cloud_notm}} region and data center locations for resource deployment](/docs/overview?topic=overview-locations).

## December 2024
{: #december-2024}

### 17 December 2024
{: #overview-dec1724}
{: release-note}

Experimental: Customize a deployable architecture from the catalog
:   You can now customize a deployable architecture by adding optional components in the {{site.data.keyword.cloud_notm}} console. Add the [Cloud automation for {{site.data.keyword.secrets-manager_short}}](https://cloud.ibm.com/catalog/7a4d68b4-cf8b-40cd-a3d1-f49aff526eb3/architecture/testing-deploy-arch-ibm-secrets-manager-5f149ae6-d781-460a-977d-c8c4171ad0fa-global){: external} deployable architecture to a project to get started.

   For more information about onboarding a deployable architecture and specifying optional components that work with it, see [Optional and swappable components for deployable architectures](/docs/secure-enterprise?topic=secure-enterprise-choose-plan-process#optional-swappable).

### 13 December 2024
{: #overview-dec1324}
{: release-note}

Service ID limits are increased with groups
:   With Service ID groups, your account can now contain up to 100,000 service IDs, with up to 2,000 service IDs in each group. Existing service IDs were added to the default group. For more information, see [Creating and working with service IDs](/docs/account?topic=account-serviceids&interface=ui#serviceids).

## November 2024
{: #novemeber-2024}

### 21 November 2024
{: #overview-nov2124}
{: release-note}

Experimental: Connect your project to a Git repository
:   You can now connect a project to a Git repository to save configurations there. By doing so, you can use your repository and the CI / CD tools of your choosing to automate pipelines on configurations. Connecting a project to a Git repository works best with a new project that doesn't contain any configurations. This is an experimental feature that is available for evaluation and testing purposes and might change without notice. For more information, see [Integrating a project with a Git repository](/docs/secure-enterprise?topic=secure-enterprise-connect-to-git).

### 12 November 2024
{: #overview-nov1224}
{: release-note}

The AI assistant is generally available
:   The AI assistant is available to help answer your questions about working in {{site.data.keyword.cloud_notm}}. In addition to being able to launch the AI assistant in the {{site.data.keyword.cloud_notm}} console, you can also ask questions from the {{site.data.keyword.cloud_notm}} CLI. For more information, see [Getting help from the AI assistant](/docs/overview?topic=overview-ask-ai-assistant).


## October 2024
{: #october-2024}

### 17 October 2024
{: #overview-october1724}
{: release-note}

Consolidated and simplified {{site.data.keyword.cloud_notm}} platform
:   {{site.data.keyword.cloud_notm}} is bringing simplification to your door. The {{site.data.keyword.cloud_notm}} platform recently consolidated and simplified services and features. Services and areas of the console are now unified into the following hubs: Infrastructure, Containers, Automation, Databases, Observability, and Security with the goal to bundle together related services to make it easier to find, deploy, and use them. Users can now easily search for new services to accelerate business-critical workloads and better manage what is already running to help ensure their business stays on top of its velocity. For more information, see [Navigating the {{site.data.keyword.cloud_notm}} console](/docs/overview?topic=overview-ui#navoptions).

Improving the account and enterprise documentation experience
:   Easily navigate enterprise information with the latest update to {{site.data.keyword.cloud_notm}} docs. Now, you can browse key information about enterprises in one location. The documentation that supports enterprise accounts is moved to [enterprise management](/docs/enterprise-management). This includes everything you need to successfully create and manage enterprise accounts, including billing and usage and getting support.

   A simplified account documentation experience is now available. You can find all information related to your account in the updated [account documentation](/docs/account), including billing and usage and getting support.

### 03 October 2024
{: #overview-october0324}
{: release-note}

Project widget updates
:   From the **Overview** tab in a project, you can now view the resource summary and configuration usage widgets to quickly get an overview of the resources and usage in your project. These widgets provide a snapshot of key metrics, such as cost and counts of resources by category, simplifying the process of monitoring and managing resources within a project.

## August 2024
{: #august-2024}

### 07 August 2024
{: #overview-august1724}
{: release-note}

Experimental: Access resources from the Resources tab
:   A link to resources is now available from the **Resources** tab in a project. If the resource exists in a different account, the console automatically switches to that account if you have access to it. If you don't have access to that account, the console displays an error message.

View counts for all resources in the resource summary widget
:   The resource summary widget for a project now shows resource counts for all resources in a project by default. The **All resources** option in the widget's menu is selected by default. To view resource counts for a specific configuration, select that configuration from the menu.

## June 2024
{: #june-2024}

### 17 June 2024
{: #overview-june1724}
{: release-note}

Experimental: Using AI to answer your questions about {{site.data.keyword.cloud_notm}}
:   Wherever you are working in the {{site.data.keyword.cloud_notm}} console, you can launch the AI assistant to help answer your questions about working in {{site.data.keyword.cloud_notm}}. The AI assistant is designed as a retrieval-augmented generation (RAG) implementation that is running against {{site.data.keyword.IBM}} large language models using IBM's [watsonx](https://www.ibm.com/products/watsonx){: external}. For more information, see [Getting help from the AI assistant](/docs/overview?topic=overview-ask-ai-assistant).

Changes to {{site.data.keyword.cloud_notm}} projects API method to list all deployed resources
:   A change was made to the [`project.config.retrieve-resources`](/apidocs/projects#list-config-resources) API method to improve its performance. This change can cause some of the resources to temporarily disappear from the **Resources** tab in your configurations. The resources were not destroyed. Redeploy the configurations to see the resources again.

Experimental: Project Resources tab
:   Manage the resources in your project in the new **Resources** tab. You can add existing resources to your project without using a configuration. To get started, see [Adding existing resources to a project](/docs/secure-enterprise?topic=secure-enterprise-organize-resources#add-existing-resources).

## May 2024
{: #may-2024}

### 31 May 2024
{: #overview-may3124}
{: release-note}

Onboarding software with usage-based pricing plans
:   In addition to free and bring your own license plans, you can now add usage-based pricing plans to software onboarded with the virtual server image delivery method, offering it as a paid integrated product in the {{site.data.keyword.cloud_notm}} catalog. For more information, see [Adding a usage-based plan](/docs/sell?topic=sell-sw-pricing#sw-pricing-usage-based) and [Onboarding a virtual server image for VPC with a plan](/docs/account?topic=account-working-catalog-vsivpc-tutorial).

   After adding a plan to your software in Partner Center, you can also manage it in your private catalog. This includes adding features, changing the plan’s state, deprecating it, or updating plan details. For more information, see [Managing software plans in catalogs](/docs/account?topic=account-sw-manage-plans).

### 18 May 2024
{: #overview-may1824}
{: release-note}

Google login and registration
:   Google is now available for {{site.data.keyword.Bluemix_notm}} login and {{site.data.keyword.Bluemix_notm}} registration. As a non-federated user, you can use your existing Google credentials to securely log in to {{site.data.keyword.Bluemix_notm}} or create a new {{site.data.keyword.Bluemix_notm}} account. [Learn more](/docs/account?topic=account-account-getting-started#signup-google).

### 06 May 2024
{: #overview-may0624}
{: release-note}

Experimental: Stack deployable architectures by using the console
:   Create more complex end-to-end solutions, without editing Terraform, by stacking deployable architectures. To get started, see [Stacking deployable architectures](/docs/secure-enterprise?topic=secure-enterprise-config-stack&interface=ui).

## April 2024
{: #apr-2024}

### 10 April 2024
{: #overview-april1024}
{: release-note}

Discover your software resources by category
:   Software resources that are deployed in your account are now able to be discovered in their associated catalog category. To quickly find your product, you can still take advantage of the console's filtering capabilities.

### 03 April 2024
{: #overview-april0324}
{: release-note}

Projects API v1.0.0
:   Version 1.0.0 of the projects API is now available. To learn more about the changes that are included in this release, see the [Projects API change log](/docs/secure-enterprise?topic=secure-enterprise-projects-api-change-log&interface=ui#03-apr-2024).

Experimental: Stacking deployable architectures
:   You can now stack deployable architectures together to create more complex end-to-end scenarios by using either the API or the CLI. To learn more about stacking deployable architectures, see [What is a deployable architecture?](/docs/secure-enterprise?topic=secure-enterprise-understand-module-da&interface=ui#what-is-da)

## March 2024
{: #mar-2024}

### 21 March 2024
{: #overview-march2124}
{: release-note}

Increased limits for enterprises
:   Easily scale your organization and workloads with increased limits on the number of accounts and account groups that you can have in your enterprise. You can have a maximum of 1000 accounts and 500 account groups.

### 05 March 2024
{: #overview-mar0524}
{: release-note}

Upgrade your Pay-As-You-Go account
:   You can now create an enterprise from Pay-As-You-Go accounts that signed up with a credit card on cloud.ibm.com. For more information, see [Billing FAQs](/docs/account?topic=account-billusagefaqs#paygo-enterprise).

## February 2024
{: #feb-2024}

### 20 February 2024
{: #overview-feb2024}
{: release-note}

Organize existing resources in your project
:   Now, you can use a project to organize resources across accounts. By doing so, your resources remain deployed in their respective accounts, but you gain an at-a-glance view of those resources in your project. Organizing resources is experimental and might change without notice. For more information, see [Organizing existing resources by using a project](/docs/secure-enterprise?topic=secure-enterprise-organize-resources).

### 06 February 2024
{: #overview-feb062024}
{: release-note}

Automatically detect drift in your project
:   You can now run a daily scan to detect any changes between your configured architecture and the actual state of your deployed resources. To fix drift, you can override the changes or adopt them. Automatic drift detection is an experimental feature and might change without notice. For more information, see [Managing Drift](/docs/secure-enterprise?topic=secure-enterprise-manage-drift).

Add references in your project
:   It's now easier to link architectures to one another by adding references to inputs or outputs. Add the reference as an input in an architecture that you're configuring, and the value is automatically used for deployment. For more information, see [referencing values](/docs/secure-enterprise?topic=secure-enterprise-config-project&interface=ui#reference-values).

Duplicate configurations in your project
:   Now, you can duplicate an architecture configuration from the Configurations tab in a project. By doing so, you can quickly create a second version of your configuration with all of the input values that were provided in the original configuration. From the **Configurations** tab, select the **Actions** icon for the configuration you want to duplicate and click **Duplicate**.

## December 2023
{: #dec-2023}

### 07 December 2023
{: #overview-dec0623}
{: release-note}

Limit access with resource attribute-based conditions
:   {{site.data.keyword.Bluemix_notm}} IAM is excited to give customers the ability to grant access based on multiple resource attribute-based conditions. With this ability, you can create a single policy with various conditions instead of individual access policies. For more information, see [Limiting access with resource attribute-based conditions](/docs/account?topic=account-iam-time-based).


## November 2023
{: #nov-2023}

### 17 November 2023
{: #overview-nov1723}
{: release-note}

Protect your private catalog and private products
:   Add an extra layer of protection to your private catalogs with context-based restrictions. Users can view the catalogs that you protect only if they satisfy your rule.

### 14 November 2023
{: #overview-nov1423}
{: release-note}

Move deployed software into a deployable architecture and manage it by using a project
:   Use the [{{site.data.keyword.cloud_notm}} Catalogs management CLI plugin](/docs/cli?topic=cli-manage-catalogs-plugin#publish-utility-create) and the [Project CLI plugin](/docs/cli?topic=cli-projects-cli#project-cli-create-command) to convert deployed software or an existing {{site.data.keyword.bpshort}} workspace and its resources into a format that is compatible with using projects to manage future deployments. For more information, see [Moving resources from a Schematics workspace into a project](/docs/secure-enterprise?topic=secure-enterprise-move-deployed-resource-project) and the white paper on [Moving to the enterprise architecture](/docs/adopt-enterprise-architecture?topic=adopt-enterprise-architecture-intro).


### 09 November 2023
{: #overview-nov0923}
{: release-note}

Onboarding virtual server images with Terraform is deprecated
:   As of 9 November 2023, the option to onboard virtual server images with Terraform is deprecated. If you onboarded software by using this delivery method before this date, your customers can still install the VSIs, but you can't provide any version updates. After 29 March 2024, onboarding virtual server images with Terraform is no longer supported as a delivery method, which means that no new virtual server images with Terraform can be onboarded. Existing VSIs in the {{site.data.keyword.cloud_notm}} catalog will be available to use, but to take advantage of version updates and ensure continued support, onboard virtual server images for Virtual Private Cloud directly. For more information, see [Onboarding a virtual server image for VPC](/docs/account?topic=account-catalog-vsivpc-tutorial).

### 06 November 2023
{: #overview-nov0623}
{: release-note}

Introducing environments and general improvements to projects API and CLI
:   You can now group configurations together within a project by using environments. Environments can also contain properties like input values that are automatically added to configurations. This release also includes updates to the projects API and CLI. The commands are normalized so they follow a regular pattern, and terminology is now aligned across our UI, CLI, and API.

   For more information on environments, see [Controlling deployments by using environments](/docs/secure-enterprise?topic=secure-enterprise-best-practices-projects#best-practice-env). For more information on updates to the projects API, see the [projects API change log](/docs/secure-enterprise?topic=secure-enterprise-projects-api-change-log). For more information on updates to the projects CLI, see the [projects CLI change log](/docs/secure-enterprise?topic=secure-enterprise-cli-change-log).

## October 2023
{: #oct-2023}

### 30 October 2023
{: #overview-oct3023}
{: release-note}

Selecting currency
:   The option to select local currency and USD is now available during {{site.data.keyword.cloud_notm}} registration for users in Canada, United Kingdom/Ireland, Italy, Spain, France, Germany, Austria, Switzerland, Belgium, the Netherlands, Luxembourg, Denmark, Norway, Sweden, Finland, Australia, and New Zealand.

### 26 October 2023
{: #overview-oct2423}
{: release-note}

Symantec VIP 2FA is deprecated
:   If you are currently using Symantec VIP as your external authentication method, you can continue to use it and add subscribers as needed until 26 October 2024. If you are not already using Symantec VIP, then you can't purchase Symantec VIP to use as your external authentication method as of 26 October 2023.

   All customers currently using Symantec VIP must migrate to {{site.data.keyword.cloud_notm}} MFA by 26 October 2024. For more information about how easy is it to migrate to this no-cost MFA option, see [Migrating to {{site.data.keyword.cloud_notm}} MFA](/docs/account?topic=account-migrate-mfa).

### 19 October 2023
{: #overview-oct1923}
{: release-note}

Partner Center Build & Grow is deprecated
:   As of 19 October 2023, Partner Center Build and Grow is no longer supported. The new simplified and unified build experience has moved to the {{site.data.keyword.IBM_notm}} Partner Plus website, where you can start enrolling. For more information, see the [Partner Plus](https://www.ibm.com/partnerplus){: external} website and enroll by clicking **Join {{site.data.keyword.IBM_notm}} Partner Plus**.

## September 2023
{: #sept-2023}

### 20 September 2023
{: #overview-sep2023}
{: release-note}

Support for onboarding third-party deployable architectures in Partner Center
:   You can now onboard deployable architectures in Partner Center and publish them to the {{site.data.keyword.cloud_notm}} catalog. A deployable architecture is cloud automation for deploying a common architectural pattern that combines one or more cloud resources that are designed for easy deployment, scalability, and modularity that solves a customer-defined problem. For more information, see [Getting set up to sell deployable architectures](/docs/sell?topic=sell-da-getting-started).

### 6 September 2023
{: #overview-sep0623}
{: release-note}

Cross-account product sharing
:   You can now share products from your private catalog with other accounts without publishing them to the {{site.data.keyword.cloud_notm}} catalog. For more information, see [Sharing private catalog offerings](/docs/account?topic=account-catalog-share&interface=ui). The administrator of the account that you want to share your product with must accept the share request to opt in to accessing the offerings that you share. For more information, see [Accepting share requests for private catalog offerings](/docs/account?topic=account-catalog-share-accept&interface=ui).

New CLI commands for cross-account product sharing
:   New `ibmcloud catalog account` commands are available for cross-account product sharing. For more information, see the [Catalogs management CLI plug-in documentation](/docs/cli?topic=cli-manage-catalogs-plugin#catalog-account-add-approval).

Expanded integration between catalogs and projects
:   You can now link a catalog with a project. A successful validation of a linked project will validate the associated version as well. For more information, see the new section [Setting up a target account](/docs/account?topic=account-catalog-cross-validation) in the docs.

Catalog and onboarding support for {{site.data.keyword.IBMz}} when deploying VSI images
:   Partners and {{site.data.keyword.cloud_notm}} users can now onboard Virtual Server Images with {{site.data.keyword.IBMz_notm}} deployment support. Navigate to your private catalog to get started adding this image. For more information, see [Onboarding software to your account](/docs/account?topic=account-create-private-catalog&interface=ui).

### 5 September 2023
{: #overview-sep0523}
{: release-note}

Centrally administer your multi-account environment
:   {{site.data.keyword.cloud_notm}} is excited to announce that you can now centrally administer access and security settings in your organization with Enterprise-managed IAM. By using enterprise IAM templates, you can quickly create and manage access groups and trusted profiles across accounts and easily ensure that all new accounts inherit the same settings. Leveraging Enterprise-managed IAM can help your organization save time and effort, reduce the risk of unauthorized access, stay compliant with industry regulations and better protect your data.  For more information, see [Best practices for assigning access in an enterprise](/docs/enterprise-management?topic=enterprise-management-access-enterprises).

### 1 September 2023
{: #overview-sep0123}
{: release-note}

{{site.data.keyword.cloud_notm}} January 2024 price changes
:   Effective 1 January 2024, prices for some services will be increasing. For more information, see [January 2024 price changes](/docs/overview?topic=overview-price-adjustments).

## July 2023
{: #july-2023}

### 25 July 2023
{: #overview-jul2523}
{: release-note}

Projects integration with {{site.data.keyword.bplong_notm}} and general improvements
:   Projects are integrated more seamlessly with {{site.data.keyword.bpshort}}, as users can now view the {{site.data.keyword.bpshort}} logs directly from their project during validation and deployment. This release also includes system improvements to deleting a project. A recent update to the Code Risk Analyzer might result in fewer validation errors for deployable architectures that include {{site.data.keyword.messagehub}} resources.

### 11 July 2023
{: #overview-jul1123}
{: release-note}

New multizone region (MZR) available in Madrid
:   Resources can be deployed to a new MZR in Madrid, Spain. There are three data centers available in the `eu-es` region: MAD02, MAD04, and MAD05. For more information about location availability, see [Locations for resource deployment](/docs/overview?topic=overview-locations).

### 6 July 2023
{: #overview-jul0623}
{: release-note}

Projects API response models update
:   The response models for all methods now enforce a lower snake case format in state values. This format needs to be expected in the response when you are calling the project and configuration endpoints. This update is a breaking change. For more information, see the [change log](/docs/secure-enterprise?topic=secure-enterprise-projects-api-change-log#06-jul-2023).


## June 2023
{: #june-2023}

### 6 June 2023
{: #overview-june0223}
{: release-note}

New event notifications for projects
:   You can now send out notifications when a deployment is complete or when resources are successfully destroyed. For more information, see the [available events for projects](/docs/secure-enterprise?topic=secure-enterprise-event-notifications-events&interface=ui#event-notifications-list).

Support for access management tags in the projects UI
:   You can now add, edit, and delete access management tags directly in the projects UI. Previously, you could manage these tags only by using the command-line interface (CLI) or API.

## April 2023
{: #april-2023}

### 25 April 2023
{: #overview-apr2423}
{: release-note}

Customized compliance validation
:   In addition to using default controls, you can specify a {{site.data.keyword.compliance_short}} attachment to validate deployable architectures that you're configuring in a project. For more information, see [Configuring the architecture](/docs/secure-enterprise?topic=secure-enterprise-config-project&interface=ui#how-to-config).

Support for deployable architectures onboarded from private or public GitHub repositories
:   You can now deploy architectures that are onboarded to the catalog from either a private or public GitHub repository. Previously, only deployable architectures onboarded from a public GitHub repository were supported.

### 17 April 2023
{: #overview-apr1723}
{: release-note}

Check out deployable architectures in the catalog
:   {{site.data.keyword.cloud_notm}} provides deployable architectures in the catalog, which are products that provide automation for the deployment of common architectural patterns that combine one or more cloud resources and are designed for scalability and modularity. Go to the catalog, and [filter by Deployable architectures](/catalog#reference_architecture) to review the growing catalog of options. For more information, see [Identifying the right infrastructure architecture](/docs/overview?topic=overview-secure-enterprise#define-architecture).

{{site.data.keyword.cloud_notm}} projects for automated IaC deployments
:   You can now configure, deploy, and monitor deployments by using DevOps best practices with projects. By using projects, you can manage Infrastructure as Code (IaC) at scale and across accounts to ensure that the configuration is always valid, secure, and compliant. [Learn more about IaC deployments with projects](/docs/secure-enterprise?topic=secure-enterprise-understanding-projects).

Onboard customized deployable architectures for your enterprise users
:   You can customize {{site.data.keyword.cloud_notm}} deployable architectures to meet your enterprise’s needs, and then leverage private catalogs to make only approved and compliant architectures available for your enterprise developers to deploy. For more information, see [Customizing an {{site.data.keyword.cloud_notm}} deployable architecture](/docs/secure-enterprise?topic=secure-enterprise-customize-from-catalog).

### 12 April 2023
{: #overview-apr1223}
{: release-note}

Specify language support for community-supported products
:   If you offer a third-party product that is supported by open source communities, you can select the languages in which support is provided when you're onboarding or managing your product in Partner Center. By providing support in multiple languages, your customers can communicate their issues in their preferred language and get support more efficiently. For more information, see [Defining your support experience](/docs/sell?topic=sell-saas-support-details&interface=ui).

### 10 April 2023
{: #overview-apr1023}
{: release-note}

View email notification history
:   You can use the Communication history page in the console to check the status of all email notifications that are sent you to verify if the emails are being delivered successfully. You can also view the last 90 days of {{site.data.keyword.cloud_notm}} email history, which can help save you time troubleshooting any delivery issues without needing to contact {{site.data.keyword.IBM_notm}} support. For more information, see [Checking the delivery status of email notifications and viewing email history](/docs/account?topic=account-viewing-notifications).

### 04 April 2023
{: #overview-apr0423}
{: release-note}

Customize the look and feel of your private catalog
:   You can enhance the appearance of your private catalog to match your brand by adding a custom banner image to your private catalogs. For more information about personalizing your private catalog, see [Branding your private catalog with a custom banner](/docs/account?topic=account-restrict-by-user#customer-banner).

Add a custom provider name for your private products
:   You can make it easier for users to search for your products added to a private catalog by specifying a custom provider name. Adding a custom provider name for your private products can help users find them quickly by using the Provider filter in the catalog. For more information, see [Providing catalog entry details](/docs/account?topic=account-cm-catalog-details#cm-catalog-entry).

## March 2023
{: #march-2023}

### 29 March 2023
{: #overview-29march23}
{: release-note}

Generate a report on the MFA status of account users
:   Users that don't meet MFA requirements leave your account vulnerable. You can now identify the users in your account that don't satisfy your MFA requirements. For more information, see [Identifying a user's MFA status](/docs/account?topic=account-id-user-mfa).

An extra layer of security for users that don't use MFA
:   {{site.data.keyword.Bluemix_notm}} recommends enabling multifactor authentication (MFA) for all users in your account, but some automation scenarios might require you to exclude specific users from your MFA requirement. For users that are excluded from MFA, you can make access more secure by disabling CLI logins with only a username and password. This way, you require an API key to log in to the CLI or users can log in with `--sso`. For more information, see [Disabling MFA](/docs/account?topic=account-enablemfa#disablemfa).

## February 2023
{: #february-2023}

### 22 February 2023
{: #overview-22feb23}
{: release-note}

User-specific MFA
:   You can now enforce user-specific multifactor authentication (MFA) requirements that differ from the account default MFA setting. After you update the MFA requirement for an individual user, view a list of users that have unique MFA requirements in the account by going to Manage > Access (IAM) > Settings > Authentication. For more information, see [Enabling MFA for an individual user](/docs/account?topic=account-enablemfa&interface=ui#enabling-user).

### 20 February 2023
{: #overview-20feb23}
{: release-note}

Download and read {{site.data.keyword.cloud_notm}} docs offline
:   While digital is still the primary delivery target for {{site.data.keyword.cloud_notm}} docs, you can now print or download and read a doc set offline. Go to the menu next to the doc set title in the navigation and click **View as PDF**.

## January 2023
{: #january-2023}

### 27 January 2023
{: #overview-27jan23}
{: release-note}

New services integrating with context-based restriction
:   Services continue to integrate with the {{site.data.keyword.Bluemix_notm}} platform's context-based restrictions feature, including [{{site.data.keyword.vpc_full}} (VPC) Infrastructure Services](/docs/vpc?topic=vpc-cbr). To see a full list of services that can use context-based restrictions to define and enforce access restrictions on their resources, see [Services integrated with context-based restrictions](/docs/account?topic=account-context-restrictions-whatis#cbr-adopters).

### 25 January 2023
{: #overview-25jan23}
{: release-note}

Time-based conditions in IAM access policies
:   {{site.data.keyword.Bluemix_notm}} IAM is excited to give customers the ability to set access controls based on a specified time and date. You can now create policies that grant employees access to a resource during only their working hours, or grant automated processes temporary access for a specified duration. Implementing such limitations helps you to apply the principle of least privilege for assigning access and reduces the opportunity for attack in the event of a security breach. For more information, see [Limiting access with time-based conditions](/docs/account?topic=account-iam-time-based&interface=ui).

IAM Policy Management API V2 release
:   A new version (`v2`) of the IAM Policy Management API is now available. This version adds a new JSON schema to support a conditional policy construct and several time-based comparison operators. These operators provide the capability to restrict access based on time and date. With time-based access control, customers can establish granular policy enforcement based on a specified time period. For more information, see the [IAM Policy Management API change log](/docs/account?topic=account-api-change-log&interface=ui)

### 09 January 2023
{: #overview-09jan23}
{: release-note}

Save and share multiple estimates by using the {{site.data.keyword.cloud_notm}} Cost Estimator
:   The {{site.data.keyword.cloud_notm}} Cost Estimator now allows a customer to save multiple estimates to their account and share those estimates with users that belong to the same account. For more information, see [Estimating your costs](/docs/account?topic=account-cost).

## December 2022
{: #december-2022}

### 15 December 2022
{: #overview-dec1522}
{: release-note}

Checklist for getting started on {{site.data.keyword.cloud_notm}}
:   A new checklist is now available in the {{site.data.keyword.cloud_notm}} docs for [Getting started on {{site.data.keyword.cloud_notm}}](/docs/overview?topic=overview-get-started-checklist). This checklist outlines the tasks for you to complete to accelerate your journey to cloud by guiding you through your account setup and organization of resources.

## October 2022
{: #october-2022}

### 10 October 2022
{: #overview-10oct2022}
{: release-note}

A new way to provide the {{site.data.keyword.cloud_notm}} docs team your feedback
:   We want to hear from you! Let us know about your experience with the {{site.data.keyword.cloud_notm}} docs or API docs by submitting your feedback from the **Feedback** button. You can tell us what you love and even what you’d like to see improved, so we can work together to ensure that you always enjoy the {{site.data.keyword.cloud_notm}} documentation.

### 07 October 2022
{: #overview-07oct2022}
{: release-note}

Setting an alternative account owner
:   As the owner of an account with classic infrastructure, you can set a trusted profile as the alternative account owner. An alternative account owner ensures that you always have a secure way to manage account ownership if your account owner leaves your organization or isn't available.

### 04 October 2022
{: #overview-04oct2022}
{: release-note}

Catalog integration with Virtual Private Cloud custom images
:   ISV Partners and {{site.data.keyword.cloud_notm}} customers can now import custom VPC images directly to their account or enterprise, or sell on the {{site.data.keyword.cloud_notm}} catalog without depending on Terraform. For more information, see [Onboarding a virtual server image for VPC](/docs/account?topic=account-catalog-vsivpc-tutorial).

## September 2022
{: #september-2022}

### 29 September 2022
{: #overview-29sept2022}
{: release-note}

Enabling {{site.data.keyword.en_full_notm}} for the notification distribution list
:   You can now easily add {{site.data.keyword.en_short}} instances to the notification distribution list and receive account-wide {{site.data.keyword.cloud_notm}} notifications. With {{site.data.keyword.en_short}}, you can choose to deliver your notifications to different destinations, including email, SMS, or webhooks. When an event of interest occurs on the {{site.data.keyword.cloud_notm}} platform and an event is generated, the notification distribution list communicates with a connected {{site.data.keyword.en_short}} instance to forward a notification to the supported destination.

For more information, see [Enabling {{site.data.keyword.en_short}} for the notification distribution list](/docs/account?topic=account-add-users-distribution-list#event-notifications-distribution-list).

### 26 September 2022
{: #overview-26sept2022}
{: release-note}

Identifying inactive policies
:   To reduce the number of policies in your account and keep only the minimum access that is necessary for each user, you can now identify the infrequently used access policies on the [Inactive policies](/iam/inactive-policies) page in the console. You can determine whether to remove the inactive policies, or in some cases, you might expect an infrequently used policy. For more information, see [Managing inactive policies](/docs/account?topic=account-iam-audit-policies&interface=ui#iam-audit-policies-list).

Exporting user access reports
:   Make sure that users have only the access that they need. Export an access policy report for any user in your account to view all of the access policies that they are assigned. For more information, see [Exporting user access policy reports](/docs/account?topic=account-iam-audit-policies&interface=ui#audit-user-access-policies).

### 22 September 2022
{: #overview-22sept2022}
{: release-note}

A new way to provide {{site.data.keyword.cloud_notm}} your feedback
:   We want to hear from you! Let us know about your experience with the {{site.data.keyword.cloud_notm}} console by submitting your feedback from the **Help** > **Send feedback** option in the console menu bar. You can tell us what you love and even what you’d like to see improved, so we can work together to ensure that you always enjoy developing on {{site.data.keyword.cloud_notm}}.

### 21 September 2022
{: #overview-21sept2022}
{: release-note}

Getting help in the console
:   You can now find the documentation and Support Center help options from a single menu item in the {{site.data.keyword.cloud_notm}} console menu bar. Check out the new **Help** option from the console menu bar that now includes your links for [Docs](/docs), the [Support Center](https://cloud.ibm.com/unifiedsupport/supportcenter), a form to give us feedback, and available guided tours.

### 16 September 2022
{: #overview-16september2022}
{: release-note}

Attaching tags on service IDs
:   In addition to tagging resources, you can now attach user tags and access management tags on service IDs. User tags help you group service IDs for usage reports, and you can use access management tags to control access to your service IDs. For more information, see [Working with tags](/docs/account?topic=account-tag&interface=ui).

Specifying a user onboarding strategy
:   If you’re [Enabling and connecting your identity provider](/docs/account?topic=account-ibm-idp-integration), you can now specify how you want to onboard users to the account upon first-time login. This way, you can add each user to your account when they log in the first time, add users to your account only if they log in and don't select a trusted profile, or never add users to your account and provide access only by using trusted profiles. For more information about trusted profiles, see [Creating trusted profiles](/docs/account?topic=account-create-trusted-profile).

### 02 September 2022
{: #overview-02september2022}
{: release-note}

Increased policy limit
:   The shared limit for IAM policies and context-based restrictions has increased from 2010 to 4020 so that you don't need to [request an increase to the limit in your account](/docs/account?topic=account-account-limits&interface=cli#limit-increase) as you grow your organizational capacity. For more information, see [Known issues and limitations](/docs/account?topic=account-known-issues).

## August 2022
{: #august-2022}

### 31 August 2022
{: #overview-31aug2022}
{: release-note}

Choose from dark or light themes in the console
:   Enjoy a customized experience in the console that matches your preferences. By default, the console uses the mode that you already have set for your device. We'd like you to be able to experience {{site.data.keyword.cloud_notm}} using a theme of your choosing. Use the Avatar icon from the console menu bar to find the options for changing your theme.

## July 2022
{: #july-2022}

### 21 July 2022
{: #overview-21july2022}
{: release-note}

Monitoring context-based restrictions
:   To help you predict how context-based restrictions might affect users, applications, and workflows, {{site.data.keyword.cloud_notm}} is excited to release report-only mode for rules. You can enable context-based restrictions during creation, or choose to set the rule to report-only mode. Using {{site.data.keyword.cloudaccesstrailshort}}, you can monitor the impact of enabled rules, or view report-only rules to see how they will affect your users, applications, and workflows without enforcing the rule. For more information, see [Monitoring context-based restrictions](/docs/account?topic=account-cbr-monitor).

### 08 July 2022
{: #overview-08july2022}
{: release-note}

Streamlined process for updating published support information in Partner Center
:   You can update support information for your published products by editing your already approved support information and then requesting an approval. After your changes are approved, you can publish the updates. For more information, see [Updating your product's support information](/docs/sell?topic=sell-saas-support-details#service-support-include-update-support-details).

## June 2022
{: #june-2022}

### 23 June 2022
{: #overview-23june2022}
{: release-note}

Onboarding software to sell on {{site.data.keyword.cloud_notm}} by using the API
:   To sell your products on {{site.data.keyword.cloud_notm}}, you can now onboard and publish by using the Partner Center Sell API, in addition to using the Partner Center experience in the console.

### 22 June 2022
{: #overview-22june2022}
{: release-note}

Identify inactive identities
:   You can create a report in the [{{site.data.keyword.cloud_notm}} console](/iam/inactive-identities) to identify which users, service IDs, trusted profiles, and API keys in your account are inactive. Removing access for inactive identities can reduce the risk of unauthorized access to your {{site.data.keyword.cloud}} resources and help you manage access more efficiently. For more information, see [Identifying inactive identities](/docs/account?topic=account-id-inactive-identities).

Updated process for assigning access
:   Assigning IAM, Classic Infrastructure, and {{site.data.keyword.ibmcf_notm}} access just got more streamlined. When assigning access, each service that you select has an in-context description. You can also find all IAM access policy and access group information for an identity under a single tab. Check out the updated process by assigning access to any user, service ID, or trusted profile.

Assign a policy for All IAM Account Management services
:   You can now assign an access policy for All IAM Account Management services, which includes the IAM Identity service, IAM Access Management service, IAM User Management service, IAM Access Groups service, and future IAM services. By assigning an access policy for a group of services, you decrease the number of policies in your account and reduce the time and effort to manage access.

### 13 June 2022
{: #overview-13june2022}
{: release-note}

Updated process for onboarding services in Partner Center
:   Partner Center has made it easier to provide required support information. The process has improved the approval process for publishing your product, and it has added consistency to all third-party product information which helps customers find the help that they need.

For more information, see [Defining your support experience](/docs/sell?topic=sell-saas-support-details).

## May 2022
{: #may-2022}

### 04 May 2022
{: #overview-may2022}
{: release-note}

Required access to view service credentials
:    When the credential level access can't be determined by comparing the access of the user and the credential, the credential is redacted. Services that support access control on resources that are allocated in the context of a service instance, such as Cloud Object Storage buckets, now require the user to have the resource-controller.credential.retrieve_all action to view service credentials.

To determine if your service is affected, review your service's documentation. For more information about the required access to view service credentials, see [Viewing a credential](/docs/account?topic=account-service_credentials&interface=ui#viewing-credentials-ui). 

## April 2022
{: #april-2022}

### 5 April 2022
{: #overview-apr0522}
{: release-note}

Onboarding virtual server images for {{site.data.keyword.powerSys_notm}}
:   You can now onboard virtual server images for {{site.data.keyword.powerSys_notm}} to private catalogs and the {{site.data.keyword.cloud_notm}} catalog. For more information about onboarding to the {{site.data.keyword.cloud_notm}}, see [Registering a virtual server image for Power Systems in {{site.data.keyword.cloud_notm}} Partner Center](/docs/sell?topic=sell-vsipower-register). For more information about onboarding to your private catalog, see [Onboarding a virtual server image for Power Systems to a private catalog](/docs/sell?topic=sell-vsipower-onboard).

Upload translations of your software by using the CLI
:   You can now download and upload translations of your software by using the CLI. For more information, see [Translating product details by using the CLI](/docs/account?topic=account-translate-product-details).

### 4 April 2022
{: #overview-apr0422}
{: release-note}

Adding custom service parameters for your service
:  If the provisioning process of your product requires additional information from your customers, you can now add custom input fields for your product in {{site.data.keyword.cloud_notm}} Partner Center. For more information, see [Adding custom service parameters for your service in Partner Center](/docs/sell?topic=sell-service-add-custom-parameters).

## March 2022
{: #march-2022}

### 25 March 2022
{: #overview-mar2522}
{: release-note}

Trusted profiles are now members of access groups
:   You can now add trusted profiles as members of access groups like other IAM identities, such as users and service IDs. For more information, see [Creating trusted profiles](/docs/account?topic=account-create-trusted-profile) and [Setting up access groups](/docs/account?topic=account-groups).

### 1 March 2022
{: #overview-mar0122}
{: release-note}

Use feature and subscription codes to create new accounts
:   When you [register for a new {{site.data.keyword.cloud_notm}} account](/registration){: external}, you can use a feature code that you received from participating in a special event or a subscription code that you received by email. Instead of verifying your identity by entering your credit card information, click the option to **Register with a code** to complete the set up of your new account.
