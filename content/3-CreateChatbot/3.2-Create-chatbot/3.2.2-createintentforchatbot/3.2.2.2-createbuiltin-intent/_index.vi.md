---
title : "Tạo Built-in intent"
date :  "2025-07-14" 
weight : 2
chapter : false
pre : " <b> 3.2.2.2 </b> "
---


#### Tạo Built-in intent

1. Truy cập đến [giao diện quản trị của AmazonLex](https://console.aws.amazon.com/lexv2/home)
  + Click on the bot we just created.
  + Click **Intents**.
  + Click **Add Intent**.
  + Chọn **Use built-in intent**.

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.11.png)

  + Chọn **QnAbotIntent**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.12.png)

  + Tại trang cấu hình intent, Kéo xuống phần **QnA configuration**.
  + Chọn **Anthropic** và **Claude V2**
  + Tại phần **Choose a knowledge store**, Chọn **Knowledge base for Amazon bedrock**
  + Điền vào ID của knowledge base ta đã tạo từ trước.
  + Click **Save Intent**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.13.png)

2. Bây giờ chúng ta đã có thể build và test chatbot.

![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.14.png)