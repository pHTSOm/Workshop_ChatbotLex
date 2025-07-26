---
title : "Đăng tải chatbot và kết nối chatbot với website"
date : "2025-07-14"
weight : 3
chapter : false
pre : " <b> 3.2.2.3 </b> "
---


#### Đăng tải và kết nối chatbot

1. Truy cập vào [Giao diện quản trị của Amazon Lex](https://console.aws.amazon.com/lexv2/home)
  + Click vào chatbot ta đã tạo.
  + Click **Versions**.
  + Click **Create Version**.
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.1.png)

  + Kéo xuống và click **Create**.

  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.2.png)

  
2. Tại thanh điều hướng bên trái click **Aliases**.
  + Click **Create Alias**.
    ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.3.png)
  + Đặt tên cho Alias và lưu lại.
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.4.png)
  + Lưu lại alias ID và ID của chatbot

  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.5.png)
  ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.6.png)

3. Mở folder website trên visual studio code:
 + Mở folder "public".
 + Mở file chatbot.html.
 + Fill in your poolID, botname, region, bot_ID, bot_alias_ID, and the bot_localeID (which is en_US in this case).
 + Điền vào những thông tin của bạn liên quan đến poolID, botname, region, bot_ID, bot_alias_ID, và bot_localeID (hiện tại là en_US tại bài này).

 ![CreateLexchatbot](/images/3.createchatbot/PublishBot5.7.png)

4. Sau khi điền chính xác những thông tin trên thì ta đã có thể chạy app với câu lệnh npm install và npm start.

![CreateLexchatbot](/images/3.createchatbot/PublishBot5.8.png)