---
title : "Tạo Knowledge base "
date :  "2025-07-14" 
weight : 1 
chapter : false
pre : " <b> 3.1. </b> "
---

1. Truy cập vào [Bảng điều khiển Amazon Bedrock](https://console.aws.amazon.com/bedrock/home)
  + Chọn **Knowledge Bases**.
  + Click **Create** và chọn **Knowledge base with vector store**.
  
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.1.png)

2. Ở bước **Provide knowledge base detail**: 
  + Chúng ta sẽ đặt tên cho Knowledge base ví dụ như: ``KnowledgeBaseforChatbotLex``
  + Chọn **Create and use a new service role**
  + Giữ những lựa chọn khác ở mặc định và sang bước tiếp theo.

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.2.png)

3. Tại bước **Configure data source**:
  + Ở phần S3 URI, chọn **browse S3**
  + Chọn bucket chúng ta đã tạo trước đó.
  + Click **Next**

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.3.png)

4. Ở bước **Configure data storage and processing**:
  + Click **Select model**
  + Tại Category, chọn **Amazon** sau đó là **Titan Embedding G1 - Text V1.2**
  + Click **Apply**

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.5.png)
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.6.png)

  + Chọn **Amazon Opensearch Serverless** cho phần **Vector store type**.
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.7.png)

5. Kiểm tra lại thông tin của knowledge base sau đó tạo.

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.8.png)

6. Sau khi tạo thành công knowledge base chúng ta cần phải sync nguồn dữ liệu cho knowledge base
  + Tại phần **Data Source** chọn vào tên nguồn dữ liệu đã tạo sau đó click **Sync**.


  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.9.png)

  + Tiếp theo chúng ta sẽ tạo chatbot.



