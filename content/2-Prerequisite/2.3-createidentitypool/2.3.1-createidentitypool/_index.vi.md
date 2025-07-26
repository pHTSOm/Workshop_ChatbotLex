---
title : "Tạo Identity Pool"
date : "2025-07-14"
weight : 1
chapter : false
pre : " <b> 2.3.1 </b> "
---


#### Create Identity Pool
1. Truy cập đến [ giao diện quản trị của dịch vụ Amazon Cognito ](https://console.aws.amazon.com/cognito/v2/home)
   + Click **Identity Pool**.
   + Click **Create Identity Pool**.

![IdentityPool](/images/2.prerequisite/001-createidentitypool.png)

2. Tại trang **Create identity pool** .
   + Ở mục **Configure Identity Pool Trust**, Chúng ta sẽ chọn Guest Access. Việc này giúp những người dùng có thể sử dụng chatbot dù cho họ chưa đăng nhập vào trang . Khi chọn Guest access, người dùng không cần đăng nhập vẫn có thể sử dụng chatbot. Hệ thống sẽ cấp thông tin xác thực tạm thời (temporary credentials) thông qua danh tính chưa xác thực (unauthenticated identity) do Amazon Cognito quản lý. Điều này giúp dễ dàng tích hợp chatbot vào website công khai mà không cần hệ thống đăng nhập., cho phép người dùng được sử dụng Lẽ một cách an toàn mà không cần phải cung cấp thông tin hay phải đăng nhập. 
   + Click Next
   

![IdentityPool](/images/2.prerequisite/002-createidentitypool.png)

3. Tại bước **Configure permissions**, chúng ta sẽ chọn tạo một IAM role mới và đặt tên là ``` RoleCognitoforChatbotLex ```.
     

![IdentityPool](/images/2.prerequisite/003-createidentitypool.png)   

4. Tại bước **Configure properties**, chúng ta sẽ chọn tên cho Identity pool ví dụ ``` LexFrontendGuestPool ```.
   
![IdentityPool](/images/2.prerequisite/004-createidentitypool.png)   

4. Cuôi cùng chúng ta sẽ xem lại thông tin và tạo identity pool.

![IdentityPool](/images/2.prerequisite/005-createidentitypool.png)   
