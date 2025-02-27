---
author: laujan
ms.service: cognitive-services
ms.subservice: translator-text
ms.topic: include
ms.date: 08/06/2019
ms.author: lajanuar
---
## Set up

### Create a Translator resource

Azure Cognitive Services are represented by Azure resources that you subscribe to. Create a resource for Translator using the [Azure portal](../../cognitive-services-apis-create-account.md) or [Azure CLI](../../cognitive-services-apis-create-account-cli.md) on your local machine. You can also:

* View an existing resource in the [Azure portal](https://portal.azure.com/).

After you get a key from your trial subscription or resource, create two [environment variables](../../cognitive-services-apis-create-account.md#configure-an-environment-variable-for-authentication):

* `TRANSLATOR_TEXT_SUBSCRIPTION_KEY` - The subscription key for your Translator resource.
* `TRANSLATOR_TEXT_ENDPOINT` - The global endpoint for Translator. Use `https://api.cognitive.microsofttranslator.com/`.