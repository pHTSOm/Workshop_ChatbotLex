---
title : "Create a knowledge base"
date : "2025-07-14"
weight : 1
chapter : false
pre : " <b> 3.1. </b> "
---

1. Go to [Amazon Bedrock console](https://console.aws.amazon.com/bedrock/home)
  + Click on **Knowledge Bases**.
  + Click **Create** and choose **Knowledge base with vector store**.
  
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.1.png)

2. In the **Provide knowledge base detail** step: 
  + We will name the knowledge base e.g: ``KnowledgeBaseforChatbotLex``
  + Choose **Create and use a new service role**
  + Keep other as default and go to the next step.

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.2.png)

3. In the **Configure data source** step:
  + At the S3 URI section, choose **browse S3**.
  + Choose the bucket we created previously.
  + Click **Next**

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.3.png)

4. In the **Configure data storage and processing** step:
  + Click on **Select model**
  + In Category, choose **Amazon** then **Titan Embedding G1 - Text V1.2**
  + Click **Apply**

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.5.png)
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.6.png)

  + Select **Amazon Opensearch Serverless** for **Vector store type**.
  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.7.png)

5. Review all the knowledge base's information carefully then create the knowledge base

  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.8.png)

6. After successfully create the knowledge base we need to sync the data source to the knowledge base.
  + Tick the knowledge base then click **Sync**.


  ![Createchatbot](/images/3.createchatbot/CreateKnowledgeBaseonBedrock3.9.png)

  + All we need to do next is create the chatbot.

