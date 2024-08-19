---

copyright:
  years: 2024
lastupdated: "2024-08-19"

keywords:

subcollection: overview

---

{{site.data.keyword.attribute-definition-list}}

# Getting help from the AI assistant
{: #ask-ai-assistant}

{{site.data.keyword.cloud}}'s AI assistant, which is powered by {{site.data.keyword.IBM}}'s watsonx, is designed to help you learn about working in {{site.data.keyword.cloud_notm}} and building solutions with the available catalog of offerings.
{: shortdesc}

The AI assistant is an experimental feature that is available for evaluation and testing purposes and might change without notice or be withdrawn. There are no warranties, SLAs, or support provided during the experimental phase. For more information, see [product release levels](/docs/overview?topic=overview-services_availability#release-levels).
{: experimental}

## What is the AI assistant?
{: #what-is-ai-assistant}

No matter where you are working in the {{site.data.keyword.cloud_notm}} console, the AI assistant is available to help with your questions about {{site.data.keyword.cloud_notm}}. The AI assistant is designed as a retrieval-augmented generation (RAG) implementation that is running against {{site.data.keyword.IBM}} large language models (LLMs) using [{{site.data.keyword.IBM_notm}}'s watsonx](https://www.ibm.com/watsonx).

You can start the AI assistant from the {{site.data.keyword.cloud_notm}} console header from the Help menu anytime you want to ask a question, and it follows along with you in the console until you close it. With each question that you ask, source citations from the {{site.data.keyword.cloud_notm}} docs are provided to ensure that you have access to additional information and the ability to verify responses. The AI assistant supports all [national languages supported by {{site.data.keyword.cloud_notm}}](/docs/overview?topic=overview-language-support), so you can ask your question and get an answer in any of the 10 supported languages.

{{site.data.keyword.cloud_notm}} does not gather any personal identifiable information when you are using the AI feature and it is not connected to or associated with your account. When you query the AI assistant, it is not being trained based on user input and does not associate any queries with your identity or account. {{site.data.keyword.IBM_notm}} endeavors to develop AI in accordance with its published principles of trust and transparency. For more information, see [AI Ethics](https://www.ibm.com/impact/ai-ethics){: external}.



## Limitations
{: #ai-assistant-limitations}

During the experimental release, the AI assistant has the following limitations:

* Questions must be limited to 300 characters or less.
* AI-generated responses are limited to information from the {{site.data.keyword.cloud_notm}} docs and the LLM.
* Actions like creating resources or making changes within your account can't be completed by the AI assistant.
* Answers from the previous query and response are not used to answer subsequent queries.


## Prompting the AI assistant
{: #asking-questions}

To help you stay productive, you can get in-context help as you're working in the {{site.data.keyword.cloud_notm}} console by prompting the AI assistant to learn more about the platform or the services that you're using.

1. From the {{site.data.keyword.cloud_notm}} console menu bar, click the **Help** icon ![Help icon](../icons/help.svg "Help") > **Launch AI (Experimental)**.
1. Ask questions about working in your account, working with products and offerings from the catalog, and more to help you be productive in {{site.data.keyword.cloud_notm}}.
1. You can use the supported product documentation sources that are returned to verify the information.

Content that is generated in the AI assistant might include mistakes or be incorrect.
{: important}

### Clearing your chat history
{: #clear-history}

All of the questions that you ask and the generated answers for each are retained in the AI assistant window until you decide that you want to clear the history. To clear the history, open the AI assistant, and then click the ![Open Menu icon](../icons/icon_hamburger.svg "Open menu") > **Clear history** option.

### Closing the AI assistant
{: #close-assistant}

The AI assistant follows along with you in the console until you close it. Click the **Close chat** icon ![Close chat icon](../icons/close-icon.svg "Close chat") when you're done asking questions. Your history is saved though, so you can see your previous questions and answers the next time that you open it.


## Tips for creating effective prompts
{: #ai-question-tips}

When you ask the AI assistant a question, you are creating a prompt that is used to generate an answer. To ensure that you get the best response, review the following tips:

Always include context
:   The more specific that you can be by including the right details, the better the response is. For example, if you're asking about a dashboard within the console for a specific service, you want to make sure to include the name of that service.

Ask questions that can be answered by the AI assistant
:   The AI assistant is limited to answering questions about {{site.data.keyword.cloud_notm}}. This means that your questions should remain about {{site.data.keyword.cloud_notm}} and its offerings.

Be clear and concise
:   You want to include enough detail to get your question answered correctly. But, including too much detail or being too verbose in your prompt might result in an incorrect answer.

Be kind and polite
:   Everyone wants to be treated kindly, even AI assistants.

Rephrase your question when needed
:   If you don't get the answer that you expected, sometimes you need to rework your prompt to provide more or less detail or use different terms and synonyms to get the right response.

Here are some examples of questions that you might ask:

* Can I customize the {{site.data.keyword.cloud_notm}} dashboard?
* What's the difference between Pay-As-You-Go and Subscription accounts?
* How can I increase my quotas for VPC resources?
* How should I organize my secrets?
* Help me learn more about Power Virtual Server
