---
title : "Cài Đặt Công Cụ CLI"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 2.1.3 </b> "
---
### 3. Cài đặt công cụ CLI

#### 3.1. Tải và cài đặt AWS Command Line Interface (CLI)

- Truy cập trang [Tải AWS CLI](https://aws.amazon.com/cli/).
- Tải phiên bản AWS CLI phù hợp với hệ điều hành của bạn:
  - **Windows**: Tải và cài đặt file `.msi` từ trang tải về của AWS.
  - **macOS**: Dùng Homebrew để cài đặt CLI, hoặc tải file `.pkg` từ trang tải của AWS.
  - **Linux**: Cài đặt AWS CLI thông qua các lệnh terminal như `curl` hoặc `apt-get` (tùy theo bản phân phối).

- Sau khi tải về, chạy file cài đặt và làm theo hướng dẫn trên màn hình để hoàn tất quá trình cài đặt.

#### 3.2. Cấu hình CLI bằng lệnh `aws configure` với Access Key và Secret Key từ AWS IAM

- Mở terminal (Command Prompt trên Windows, Terminal trên macOS/Linux).
- Chạy lệnh sau để cấu hình AWS CLI:
- Hệ thống sẽ yêu cầu bạn nhập các thông tin sau:
- **AWS Access Key ID**: Nhập Access Key mà bạn đã tạo từ IAM trong AWS Console.
- **AWS Secret Access Key**: Nhập Secret Key mà bạn đã tạo từ IAM.
- **Default region name**: Nhập khu vực (Region) mặc định mà bạn muốn sử dụng cho các dịch vụ AWS (ví dụ: `us-west-2`).
- **Default output format**: Chọn định dạng xuất ra (json, text, hoặc table). Thường chọn `json` cho định dạng dễ sử dụng.

Sau khi hoàn thành, AWS CLI sẽ được cấu hình và sẵn sàng sử dụng.
