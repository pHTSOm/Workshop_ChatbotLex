---
title : "Thêm policy cho Role"
date :  "2025-07-14" 
weight : 2
chapter : false
pre : " <b> 2.3.2 </b> "
---

#### Thêm policy vào role của Identity Pool đã tạo

1. Truy cập vào **Bảng điều khiển IAM**.
  + Chọn **Roles**
  + Tìm đến role của Identity Pool vừa tạo và chọn vào, đối với tôi trong trường hợp này role của tôi có tên là **RoleCognitoforChatbotLex**

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.1.png)

2. Kéo xuống và tìm thẻ **Permissions**
  + Click **Add permissions**.
  + Chọn **Create inline policy**.

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.2.png)

3. Copy policy này vào Policy editor và lưu lại.
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

4. Chúng ta đã thành công thêm policy cho role.

![AttachPolicy](/images/2.prerequisite/AttachPolicytoRole2.4.png)
  
