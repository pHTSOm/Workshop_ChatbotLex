---
title : "Publish and connect chatbot to website"
date : "2025-07-14"
weight : 3
chapter : false
pre : " <b> 3.2.2.3 </b> "
---


#### Publish and connect the chatbot

1. Go to [Amazon Lex service management console](https://console.aws.amazon.com/lexv2/home)
  + Click on the bot we just created.
  + Click **Versions**.
  + Click **Create Version**.
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.1.png)

  + Scroll down and click **Create**.

  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.2.png)

  
2. At the left navigation bar click **Aliases**.
  + Click **Create Alias**.
    ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.3.png)
  + Name the alias and save it.
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.4.png)
  + Save the alias ID and the bot ID

  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.5.png)
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.6.png)

3. Open the website folder on visual studio code:
 + Open the "public" folder
 + Open "chatbot.html" file
 + Fill in your poolID, botname, region, bot_ID, bot_alias_ID, and the bot_localeID (which is en_US in this case).

 ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.7.png)

4. After fill in all the information to chatbotconfig correctly we can run the app with npm start

![CreateLexchatbot](/images/3.createchatbot/PublishBot5.8.png)