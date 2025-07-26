---
title : "Preparation "
date : "2025-07-14"
weight : 1
chapter : false
pre : " <b> 2. </b> "
---


To connect the Lex chatbot with our website, we will first construct an identity pool and apply the relevant IAM policy to its role, allowing for safe communication with the chatbot.  Next, we'll seek access to the foundation model employed by the Amazon Bedrock knowledge base.  Finally, we will upload an imitation policy file to Amazon S3 to act as a knowledge source for the knowledge base that powers the chatbot that operates on our store's website.

### Content
  - [Preparing Identity pool and clone website](2.1-createidentitypool/)
  - [Request necessary model for Amazon Bedrock knowledge base ](2.2-requestmodel/)