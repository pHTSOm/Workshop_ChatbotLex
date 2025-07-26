---
title : "Create Built-in intent"
date : "2025-07-14"
weight : 2
chapter : false
pre : " <b> 3.2.2.2 </b> "
---


#### Create Built-in intent

1. Go to [Amazon Lex service management console](https://console.aws.amazon.com/lexv2/home)
  + Click on the bot we just created.
  + Click **Intents**.
  + Click **Add Intent**.
  + Choose **Use built-in intent**.

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.11.png)

  + Choose **QnAbotIntent**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.12.png)

  + In the intent configuration page, scroll down to **QnA configuration**
  + Choose **Anthropic** and **Claude V2**
  + At the **Choose a knowledge store**, Choose **Knowledge base for Amazon bedrock**
  + Fill in the knowledge base's ID we have created before.
  + Click **Save Intent**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.13.png)

2. Now we can build and test the bot.

![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.14.png)