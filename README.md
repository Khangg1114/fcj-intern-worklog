# fcj-intern-worklog
Worklog thực tập tại FCJ – Họ và tên: Nguyễn Hà An Khang

## 📅 Ngày: 12/05/2025
- ⏰ Thời gian làm việc: 15:30 - 19:30

### ✅ Công việc đã hoàn thành:
- Tạo mới tài khoản AWS, kích hoạt MFA cho cả Root User và IAM User.
- Tìm hiểu về User Groups, Users, Role và Policies.

### ⚠️ Khó khăn gặp phải:
- Mới thao tác trên AWS Console nên còn hơi chậm.

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Tiếp tục học các phần tiếp theo trong chuỗi AWS Study Group( AWS Identity and Access Management, Amazon EC2, VPC & Site-to-Site VPN ).

![Day1-Pic1](https://imgur.com/3VBlSJ3.jpeg)

------------------------------------------------------------------------------------------------------------------------------------------
## 📅 Ngày: 13/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Thiết lập policies và roles IAM cho các user groups trong AWS.
- Sử dụng thử các phiên bản Amazon EC2 và cấu hình các nhóm bảo mật cho các dịch vụ khác nhau.

### ⚠️ Khó khăn gặp phải:
- Gặp một số khó khăn trong việc cấu hình EC2

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Tiếp tục thực hành cho đến lab07

![Day2-Pic1](https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747398104/v0hq7t4exd78vc8jkdvj.jpg)
  
------------------------------------------------------------------------------------------------------------------------------------------
## 📅 Ngày: 14/05/2025
- ⏰ Thời gian làm việc: 13:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tạo được cost budget.
- Hiểu được tầm quan trọng của việc tạo budget và cách tạo các loại budget bằng template có sẵn của AWS.

### ⚠️ Khó khăn gặp phải:
- Chưa sử dụng tài nguyên nào nên chưa biết budget hoạt động ra sao

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Làm lab về VPC và EC2

![Day3-Pic1](https://imgur.com/RtcQVaP.jpeg)

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 15/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Hiểu được việc vận dụng AWS Well-Architected Framework giúp cải thiện kiến trúc hệ thống theo 6 trụ cột: vận hành hiệu quả, bảo mật, độ tin cậy, hiệu suất, tối ưu chi phí và tính bền vững, từ đó xây dựng solution trên nền tảng AWS.
- Biết được các khái niệm như: VPC, Subnet, Route Table, Internet Gateway, NAT Gateway và các phương thức bảo mật như: NACL, Security group

### ⚠️ Khó khăn gặp phải:
- Còn mơ hồ chưa hiểu rõ, phải nhìn vào sơ đồ ví dụ thì mới dễ hiểu

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Thực hành tạo các thành phần trong VPC

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 16/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Create VPC, Subnet, Internet Gateway, Route Table, Security Group
- Xem lại các khái niệm để hiểu rõ hơn về cấu trúc

### ⚠️ Khó khăn gặp phải:
- Phải tự tìm hiểu thêm thì mới hiểu hết được chi tiết các thành phần 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Thực hành tạo máy chủ EC2

<p align="center">
  <img src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747401077/j2zgty8d7o2alsgkxzu7.jpg" width="300"/>
  <img src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747401087/zf10jok1lwtusnbskkfp.jpg" width="300"/>
  <img src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747401029/ukwlydy3aovnpqtmtyge.jpg" width="300"/>
</p>

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 17/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tạo máy chủ EC2, kiểm tra kết nối,  tạo NAT Gateway, sử dụng Reachability Analyzer, tạo EIC Endpoint

### ⚠️ Khó khăn gặp phải:
- Lỗi khi kết nối tới SSH khi dùng VS Code.
- Lỗi không add EIC Endpoint - SG vào Private subnet - SG nên  không Connect using EC2 Instance Connect Endpoint khi dùng EC2 Private Instance.

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Tiếp tục cấu hình Site to Site VPN để kết nối 2 VPC

<p align="center">
  <img alt="AllInstances" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747489875/dhvpwxcm86w9wosdk6fu.jpg" width="400"/>
  <img alt="useEC2PublicConectToPrivateIP" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747489828/ychckwducvxgowjhhslq.jpg" width="400"/>
  <img alt="UsePrivateinstanceConect" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747489804/hjeahuqxq3d9n3h6uq7i.jpg" width="400"/>
  <img alt="UseEC2EIC" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747489789/ga9k4pdnsymxppk91ddz.jpg" width="400"/>
</p>

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 18/05/2025
- ⏰ Thời gian làm việc: 09:30 - 14:30

### ✅ Công việc đã hoàn thành:
- Tạo môi trường VPN: tạo thêm VPC và một ECS Instance
- Cấu hình kết nối VPN: tạo kết nối VPN, cấu hình Customer Gateway

### ⚠️ Khó khăn gặp phải:
- Lỗi không tải được openswan do dùng Amazon Linux 2023

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Set up Hybrid DNS with Route 53 Resolver

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 19/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tạo CloudFormation Template
- Kết nối đến RDGW
- Triển khai Microsoft AD và thiết lập DNS

### ⚠️ Khó khăn gặp phải:
- 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Set up VPC peering

![Day8-Pic1](https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747634140/xdhhdesyxobta0rv5e9z.jpg)

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 20/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tạo CloudFormation Template, SG, EC2 instance
- Cập nhật NACL
- Tạo kết nối Peering và configure Route Tables
- Kích hoạt Cross-Peer DNS

### ⚠️ Khó khăn gặp phải:
- Bị lỗi không kết nối được tới private IP do chưa set route table

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Set up AWS Transit Gateway

<p align="center">
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747724251/utepwjx2pixys0jdepi0.jpg" width="400"/>
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747724279/aliypwfcjmtasjxi57kf.jpg" width="400"/>
</p>

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 21/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tạo Transit Gateway, TGW Attachments, TGW ransit Gateway Route Tables
- Thêm Transit Gateway Routes vào VPC Route Tables
- Sử dụng AWS Reachability Analyzer để kiểm tra kết nối giữa 2 Instances

### ⚠️ Khó khăn gặp phải:
- 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Compute VM on AWS

![Day10-Pic1](https://res.cloudinary.com/dqnwg2tlu/image/upload/v1747809394/ek3axvn4doercc7hevyp.jpg)

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 22/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Tìm hiểu về các tính năng dịch vụ trên Amazon EC2, Amazon Lightsail, Amazon EFS/FSX, AWS MGN
- Đọc phần 1 chap 1 của cuốn AWS Certified Advanced Networking Study Guide: Specialty (ANS-C01) Exam, 2nd Edition

### ⚠️ Khó khăn gặp phải:
- 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Deploy AWS Backup to the System Lab

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 26/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Create Backup plan
- Setup notifications
- Test Restore

### ⚠️ Khó khăn gặp phải:
- Giao diện cấu hình khác với hướng dẫn có nhiều tính năng hơn

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Using AWS Storage Gateway

<p align="center">
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748232866/xo6tjytryf3hianmtdp0.jpg" width="400"/>
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748232880/xawdpytavsniiot2zv1p.jpg" width="400"/>
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748232891/i3yai3xtghxkhkgidwif.jpg" width="400"/>
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748232903/c3rdlykwx7ook51ljv1o.jpg" width="400"/>
</p>

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 27/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Create S3 bucket & EC2 for Storage Gateway
- Create Storage Gateway
- Create File Shares & Mount File shares on On-premises machine

### ⚠️ Khó khăn gặp phải:
- 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Using Amazon Simple Storage Service (Amazon S3)

<p align="center">
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748390268/x2wjtijicvlwhsrhqvjv.jpg" width="400"/>

</p>

------------------------------------------------------------------------------------------------------------------------------------------

## 📅 Ngày: 28/05/2025
- ⏰ Thời gian làm việc: 09:30 - 16:30

### ✅ Công việc đã hoàn thành:
- Create S3 bucket & load data
- Config Amazon CloudFront
- Move objects & Replication Oject multi Region

### ⚠️ Khó khăn gặp phải:
- 

### 🗓️ Kế hoạch cho ngày tiếp theo:
- Tìm hiểu về dịch vụ lưu trữ trên AWS

<p align="center">
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748489119/fpdfbbwifstwy19q5u66.jpg" width="400"/>
  <img alt="" src="https://res.cloudinary.com/dqnwg2tlu/image/upload/v1748489133/odi13hdecutzxnjdl8uy.jpg" width="400"/>
</p>
