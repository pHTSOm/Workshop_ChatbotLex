---
title : "Attach Policy to Role"
date : "2025-07-14"
weight : 2
chapter : false
pre : " <b> 2.3.2 </b> "
---

#### Attach Policy to Identity Pool's role

1. Go to **IAM management console**.
  + Click **Roles**.
  + Find the Identity Pool's role we just created and click it, for me in this case is **RoleCognitoforChatbotLex**.

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.1.png)

2. Scroll down and find the **Permissions** tag.
  + Click **Add permissions**.
  + Choose **Create inline policy**.

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.2.png)

3. Copy this policy to Policy editor and save it.
```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Statement1",
      "Effect": "Allow",
      "Action": [
        "lex:StartConversation",
        "lex:RecognizeText",
        "lex:RecognizeUtterance"
      ],
      "Resource": [
        "*"
      ]
    },
    {
      "Sid": "Statement2",
      "Effect": "Allow",
      "Action": ["cognito-identity:GetCredentialsForIdentity"],
      "Resource": ["*"]
    }
  ]
}

```

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.3.png)

4. We have successfully attach new policy to role.

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.4.png)
  