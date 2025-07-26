+++
title = "Clean up resources"
date = 2025
weight = 4
chapter = false
pre = "<b>4. </b>"
+++

We will take the following steps to delete the resources we created in this workshop.

#### Delete OpenSearch

1. Go to [Amazon OpenSearch service management console](https://console.aws.amazon.com/aos/home)
   + Click **Dashboard**.
   + Select **Bedrock Knowledge base**.
   + Click **Delete** 
   + Input "confirm" to delete

![Clean](/images/4.clean/DeleteOpenSearch2.1.png)   
![Clean](/images/4.clean/DeleteOpenSearch2.2.png)   


#### Delete chatbot

1. Go to [Amazon Lex service management console](https://console.aws.amazon.com/lexv2/home)
   + Click **Bots**.
   + Check the bot.
   + Click **Action**.
   + Choose **Delete**
   + Confirm delete.

   
![Clean](/images/4.clean/Deletebot1.1.png)   
![Clean](/images/4.clean/Deletebot1.2.png)


#### Delete Identity pool

1. Go to [Amazon Lex service management console](https://console.aws.amazon.com/cognito/v2/home)
   + Click on **Identity pools**.
   + Check the indentity pool then click **Delete**
   + Enter the identity pool's name to confirm delete

![Clean](/images/4.clean/DeleteCognito3.1.png)
![Clean](/images/4.clean/DeleteCognito3.2.png)

#### Delete Knowledge Base

1. Go to [Amazon Bedrock console](https://console.aws.amazon.com/bedrock/home)
   + Click **Knowledge Bases**.
   + Check the knowledge base
   + Click **Delete**.
   + Confirm delete.

![Clean](/images/4.clean/DeleteKnowledgbase4.1.png)   
![Clean](/images/4.clean/DeleteKnowledgbase4.2.png)   

#### Delete S3 bucket

1. Go to [Amazon S3 console](https://console.aws.amazon.com/s3/home)
   + Choose the policy bucket.
   + Click **Delete**.
   + Confirm delete.
![Clean](/images/4.clean/DeleteS3bucket5.1.png)   
![Clean](/images/4.clean/DeleteS3bucket5.2.png)   