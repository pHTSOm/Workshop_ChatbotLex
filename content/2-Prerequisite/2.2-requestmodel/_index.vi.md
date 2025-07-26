---
title : "Tạo IAM Role"
date :  "2025-07-14" 
weight : 2 
chapter : false
pre : " <b> 2.2 </b> "
---

### Request model
{{%notice tip%}}

**Titan Embedding G1 - Text** chỉ có thể dùng ở những khu vực như us-east-1 và us-west-2. Nên nhớ chuyển sang khu vực này trước khi tiếp tục section tiếp theo.

{{%/notice%}}

In this step, we will proceed to request access to some models we will use for Amazon Bedrock knowledge base

Ở bước, này chúng ta sẽ yêu cầu truy cập và các model chúng ta cần sử dụng cho knowledge base của Amazon Bedrock

1. Truy cập vào [Bảng điều khiển Amazon Bedrock](https://console.aws.amazon.com/bedrock/home)
2. Ở thanh điều hướng bên trái, click **Model Access**.
3. Trỏ con trỏ chuột vào **Available to request** sau đó click **Request model access**.

![RequestAccess](/images/2.prerequisite/RequestAccessforTitanEmbeddingsG1-Text1.1.png)

4. Ở trang **Edit model access** chọn những model sau:
  + Titan Embeddings G1 - Text.
  + Claude
  

![RequestAccess](/images/2.prerequisite/RequestAccessforTitanEmbeddingsG1-Text1.2.png)
![RequestAccess](/images/2.prerequisite/RequestAccessforTitanEmbeddingsG1-Text1.3.png)

5. Click **Next** 

6. Click **Submit**

7. Đợi một vài giây và chúng ta đã có quyền truy cập vào những model cần thiết.