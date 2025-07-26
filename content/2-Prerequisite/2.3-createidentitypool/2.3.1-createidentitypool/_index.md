---
title : "Create Identity Pool"
date : "2025-07-14"
weight : 1
chapter : false
pre : " <b> 2.3.1 </b> "
---


#### Create Identity Pool
1. Go to [Amazon Cognito service management console](https://console.aws.amazon.com/cognito/v2/home)
   + Click **Identity Pool**.
   + Click **Create Identity Pool**.

![IdentityPool](/images/2.prerequisite/001-createidentitypool.png)

2. At the **Create identity pool** page.
   + In the **Configure Identity Pool Trust** step, we will enable Guest Access. This lets anonymous visitors interact with the chatbot without logging in or providing AWS credentials. Guest access provides temporary credentials through Amazon Cognito’s unauthenticated identities, allowing secure use of Lex without exposing sensitive resources or requiring sign-in. 
   + Click Next
   

![IdentityPool](/images/2.prerequisite/002-createidentitypool.png)

3. In the **Configure permissions** step, we will choose create a new IAM role then name it ``` RoleCognitoforChatbotLex ```.
     

![IdentityPool](/images/2.prerequisite/003-createidentitypool.png)   

4. In the **Configure properties** step, we will give the identity pool a name e.g ``` LexFrontendGuestPool ```.
   
![IdentityPool](/images/2.prerequisite/004-createidentitypool.png)   

4. Finally we will review the information again then create the identity pool

![IdentityPool](/images/2.prerequisite/005-createidentitypool.png)   
