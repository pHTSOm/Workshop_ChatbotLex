---
title : "Create Intent manually"
date : "2025-07-14"
weight : 1
chapter : false
pre : " <b> 3.2.2.1 </b> "
---


#### Create Intent manually

1. Go to [Amazon Lex service management console](https://console.aws.amazon.com/lexv2/home)
  + Click on the bot we just created.
  + Click **Intents**.
  + Click **Add Intent**.
  + Choose **Add empty intent**.
  + We will name the intent as ``WelcomeIntent``.

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.5.png)

2. At the **Sample utterances** section.
  + We can enter some sample query that fix the context of the intent, for example: hi, hello, ola,...
  
  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.6.png)

3. At the **Initial response** section.
  + We can provide messages that acknowledge the user's first request.
  + We can configure the bot to wait for the next input by setting in **Advance Options**.
  
  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.7.png)

  + In **Advance Options**, Click **Set values** then choose **Wait for users input**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.8.png)

  + Choose **Save Intent**
  
4. We can now build and test the bot

![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.9.png)
![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.10.png)