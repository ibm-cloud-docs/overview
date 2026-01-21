---

copyright:
  years: 2024, 2026
lastupdated: "2026-01-21"

keywords: AI assistant, AI help

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Getting help from the AI assistant
{: #ask-ai-assistant}

The {{site.data.keyword.cloud}} AI assistant, which is powered by {{site.data.keyword.IBM}} watsonx, is designed to help you learn about working in {{site.data.keyword.cloud_notm}} and building solutions with the available catalog of offerings.
{: shortdesc}

The AI assistant is designed as a retrieval-augmented generation (RAG) implementation that is running against {{site.data.keyword.IBM}} large language models (LLMs) using [{{site.data.keyword.IBM_notm}}'s watsonx](https://www.ibm.com/products/watsonx){: external} and the {{site.data.keyword.cloud_notm}} docs.



{{site.data.keyword.cloud_notm}} does not gather any personal identifiable information when you are querying the AI assistant. When you query the AI assistant, it is not being trained based on user input and does not associate any queries with your identity or account. {{site.data.keyword.cloud_notm}} is using your account information only to generate customized responses in the AI assistant and is not tracking or using your account data to train AI models. {{site.data.keyword.IBM_notm}} endeavors to develop AI in accordance with its published principles of trust and transparency. For more information, see [Responsible AI](https://www.ibm.com/trust/responsible-ai){: external}.

The AI assistant responds in all [national languages that are supported by {{site.data.keyword.cloud_notm}}](/docs/overview?topic=overview-language-support) including Brazilian Portuguese, English, French, German, Japanese, Korean, Italian, Spanish, Simplified Chinese, and Traditional Chinese. To get responses from the AI assistant in one of the supported languages, ask your question in one of the languages and get an answer back in that same language.
{: note}


## Using the AI assistant in the {{site.data.keyword.cloud_notm}} console
{: #ai-assistant-console}


No matter where you are working in the {{site.data.keyword.cloud_notm}} console, the AI assistant is available to help with your questions about {{site.data.keyword.cloud_notm}} so that you can learn more about the platform or the services that you're using. Additionally, if you're experiencing a technical account or billing issue, you can use the AI assistant in the console to contact support by chatting with a live agent, depending on your support plan. You can also get the status of open cases in the account that you have access to view or manage.

### Asking a question in the AI assistant
{: #ask-about-cloud}

Start the AI assistant from the {{site.data.keyword.cloud_notm}} console header from the Help menu anytime that you want to ask a question, and it follows along with you in the console until you close it. With each question that you ask, reference citations from the {{site.data.keyword.cloud_notm}} docs are provided.

1. From the {{site.data.keyword.cloud_notm}} console menu bar, click the **Help** icon ![Help icon](../icons/help.svg "Help") > **AI assistant**.
1. Ask questions about working in your account, working with products and offerings from the catalog, and more to help you stay productive in {{site.data.keyword.cloud_notm}}.
1. Use the supported documentation references that are returned to have access to additional information and the ability to verify responses.

Content that is generated in the AI assistant might include mistakes or be incorrect.
{: important}

### Chatting with a live support agent
{: #chat-with-support}

If you have a paid support plan, you can chat with a live agent by entering `agent` in the chat from the console. With a Basic support plan, you can chat with a live agent about account and billing issues only. With an Advanced or Premium plan, you can also get technical support. Initiating a chat with a live support agent isn't supported in the CLI.

1. From the {{site.data.keyword.cloud_notm}} console menu bar, click the **Help** icon ![Help icon](../icons/help.svg "Help") > **AI assistant**.
1. Enter **agent**.
1. Choose from **Cloud Technical Support**, **Software SaaS Support**, or **Cloud Account & Billing Support**.
    - Select **Cloud Technical Support** for native cloud services, like {{site.data.keyword.logs_full_notm}} or {{site.data.keyword.containershort_notm}}, and for infrastructure services such as Storage, Networking, or Security.
    - Select **Software SaaS Support** for any software applications that you use, like watsonx, {{site.data.keyword.apiconnect_short}}, {{site.data.keyword.Db2_on_Cloud_short}}, or {{site.data.keyword.speechtotextshort}}.
1. Select a topic that relates to your question to be transferred to a live agent and start your chat.

When you chat with a live support agent, English and Japanese are the two supported languages.
{: note}

### Getting support case status
{: #support-case-status}

You can use the AI assistant in the console to get a quick status on the open cases in the account, if you have the correct access assigned. As an account owner, you have access to all cases, but if you're not the account owner, you must be assigned a specific access policy to view and manage cases. For more information about the required access to work with cases see, [Managing access to support cases](/docs/account?topic=account-access-cases).

1. From the {{site.data.keyword.cloud_notm}} console menu bar, click the **Help** icon ![Help icon](../icons/help.svg "Help") > **AI assistant**.
1. Enter **case status** to get a list of all open cases that you have access to, or enter a case number to view the current status of a specific support case.

Alternatively, you can always go to the [Manage cases](/unifiedsupport/cases){: external} page to review and work with your support cases.

### Submitting feedback for generated responses
{: #ai-feedback}

You can provide feedback for each response from the AI assistant by using the **Good response** icon ![Good response icon](images/thumbs-up.svg "Good response") and **Bad response** icon ![Bad response icon](images/thumbs-down.svg "Bad response") options. You can choose to just mark the provided answer as a good response or bad response, and you can provide feedback by selecting from a common set of qualities that describe why you chose the rating and add additional feedback in the form of a comment. Your feedback is not used to train or enhance AI models.

### Clearing your chat history
{: #clear-history}

All of the questions that you ask and the generated responses are retained in the AI assistant until you decide that you want to clear the history. To clear the history, open the AI assistant, and then click **Open menu** icon ![Open menu icon](../icons/icon_hamburger.svg "Open menu") > **Clear history**.

### Closing the chat
{: #close-assistant}

The AI assistant follows along with you in the console until you close it. You can move it to position it wherever you'd like on the page. When you're ready to close it, click the **Close** icon ![Close icon](../icons/close-icon.svg "Close"). Your history is saved even when you close the AI assistant, so you can see your previous questions and answers the next time that you open it.


## Using the AI assistant in the {{site.data.keyword.cloud_notm}} CLI
{: #ai-assistant-cli}

You can ask the AI assistant questions in the {{site.data.keyword.cloud_notm}} CLI. The `ibmcloud assist` command is also available for use in Cloud Shell.

1. Log in with the `ibmcloud login` command. If you are logging in with a federated ID, use the `--sso` option to authenticate with a one-time passcode, or use the `--apikey` option to authenticate with an API key.
2. Ask a question with the `ibmcloud assist` command.
   ```bash
   ibmcloud assist "How do I update the CLI?"
   ```
   {: codeblock}

Chatting with a live support agent and requesting case status in the AI assistant is not supported in the CLI or Cloud Shell.
{: note}

For more information about using the AI assistant in the {{site.data.keyword.cloud_notm}} CLI, see [General IBM Cloud CLI (ibmcloud) commands](/docs/cli?topic=cli-ibmcloud_cli#ibmcloud_assist).


## Limitations
{: #ai-assistant-limitations}

The AI assistant has the following limitations:

* Questions must be limited to 1000 characters or less.
* AI-generated responses are limited to information from the {{site.data.keyword.cloud_notm}} docs and the LLM.
* Actions like creating resources or making changes within your account can't be completed by the AI assistant.
* Answers from the previous query and response are not used to answer subsequent queries.
* If you encounter any styling issues in the console, use the **Open menu** icon ![Open menu icon](../icons/icon_hamburger.svg "Open menu") > **Clear history** option, and refresh the page.
* Speech to text is unavailable in the Firefox browser.




## Tips for creating effective prompts
{: #ai-question-tips}

When you ask the AI assistant a question, you are creating a prompt that is used to generate an answer. To ensure that you get the best response, review the following tips:

Always include context
:   The more specific that you can be by including the right details, the better the response is. For example, if you're asking about a dashboard within the console for a specific service, you want to make sure to include the name of that service.

Ask questions that can be answered by the AI assistant
:   The AI assistant is limited to answering questions about {{site.data.keyword.cloud_notm}}. This means that your questions should remain about {{site.data.keyword.cloud_notm}} and its offerings.

Be clear and concise
:   You want to include enough detail to get your question answered correctly. But including too much detail or being too verbose in your prompt might result in an incorrect answer.

Be kind and polite
:   Everyone wants to be treated kindly, even AI assistants.

Rephrase your question when needed
:   If you don't get the answer that you expected, sometimes you need to rework your prompt to provide more or less detail or use different terms and synonyms to get the right response. For example, if you are looking for CLI instructions instead of console instructions, you might need to specify that you want information about a specific command to complete your task.

Here are some examples of questions that you might ask:

* What's the difference between Pay-As-You-Go and Subscription accounts?
* How can I increase my quotas for VPC resources?
* How should I organize my secrets?
* Help me learn more about Power Virtual Server
