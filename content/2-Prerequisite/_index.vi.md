---
title : "Các bước chuẩn bị"
date :  "2024-01-15" 
weight : 2 
chapter : false
pre : " <b> 2. </b> "
---

Để kết nối chatbot Lex với trang web của chúng ta, trước tiên chúng ta sẽ tạo một identity pool và gắn policy IAM phù hợp cho vai trò (role) liên quan, nhằm đảm bảo khả năng giao tiếp an toàn với chatbot. Tiếp theo, chúng ta sẽ yêu cầu quyền truy cập vào model được sử dụng bởi Amazon Bedrock Knowledge Base. Cuối cùng, chúng ta sẽ tải lên một tệp policy mẫu vào Amazon S3 để sử dụng làm nguồn kiến thức cho knowledge base, cung cấp thông tin cho chatbot hỗ trợ trên trang web của cửa hàng.

### Nội dung
  - [Tạo Identity pool và clone website](2.1-createidentitypool/)
  - [Yêu cầu model cần thiết cho Amazon Bedrock ](2.2-requestmodel/)

  
