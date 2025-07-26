---
title : "Tạo Intent thủ công "
date :  "2025-07-14" 
weight : 1
chapter : false
pre : " <b> 3.2.2.1 </b> "
---


#### Tạo  thủ công

1. Truy cập đến [Giao diện quản trị của Amazon Lex](https://console.aws.amazon.com/lexv2/home)
  + Click vào chatbot ta đã tạo.
  + Click **Intents**.
  + Click **Add Intent**.
  + Chọn **Add empty intent**.
  + Chúng ta sẽ đặt tên cho Intent này là ``WelcomeIntent``.

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.5.png)

2. Ở phần **Sample utterances** .
  + Chúng ta có thể thêm một vài câu truy vấn mà người dùng có thể cho như là: hi, hello, ola,...
  
  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.6.png)

3. Tại phần **Initial response** .
  + Chúng ta có thể cung cấp những tin nhắn nhận biết được yêu cầu của người dùng. 
  + Chúng ta có thể tuỳ chỉnh cho con chatbot đợi câu truy vấn tiếp theo của người sử dụng tại phần **Advance Options**
  
  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.7.png)

  + Tại phần **Advance Options**, Click **Set values** sau đó chọn **Wait for users input**

  ![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.8.png)

  + Chọn **Save Intent**
  
4. Bây giờ chúng ta đã có thể build và test chatbot.

![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.9.png)
![CreateLexchatbot](/images/3.createchatbot/CreateChatbotLex4.10.png)