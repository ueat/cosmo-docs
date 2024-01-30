---
description: Cosmo AI is currently in open beta.
---

# Cosmo AI

Cosmo Cloud now features an array of non-production capabilities utilizing LLM providers like OpenAI, designed to enhance your workflows. These include the automatic generation of documentation for your graphs and assistance in fixing queries. Upon publishing a schema, Cosmo Cloud sends a request to the LLM, which contains your prompt and the GraphQL schema. It's important to note that the LLM does not gain access to any other data stored in our Cloud. For more details on data handling, please refer to [OpenAI's](https://openai.com/enterprise-privacy) privacy policies.

### Capabilities

* **Generate Subgraph Documentation:** When you [publish](../cli/subgraph/publish.md) a Subgraph for the first time, Cosmo Cloud automatically generates the README (documentation) based on the provided GraphQL schema. This process is executed in the background and typically completes within about 30 seconds.

{% hint style="info" %}
Schemas exceeding 10,000 characters are ignored. However, if you're interested in trying it out, please inform us. Our capacity is limited due to the beta phase.
{% endhint %}