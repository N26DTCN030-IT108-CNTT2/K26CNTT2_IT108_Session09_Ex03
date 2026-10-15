# SOURCE CODE
# Hướng dẫn cài đặt và sử dụng VS Code cho lập trình viên mới

Tài liệu này cung cấp các bước cơ bản để thiết lập môi trường lập trình tối ưu trên Visual Studio Code.

## 1. Khối mã nguồn Python mẫu

Dưới đây là đoạn script Python kiểm tra hệ thống và in ra lời chào:

``` python
import sys

def chao_mung():
    print(f"Phiên bản Python hiện tại: {sys.version}")
    print("Chào mừng bạn đến với môi trường phát triển chuyên nghiệp!")

if __name__ == "__main__":
    chao_mung()
```


2. Bảng so sánh công cụ: StackEdit vs. VS Code
| Tiêu chí | StackEdit | Visual Studio Code (VS Code) |
| :--- | :--- | :--- |
| **Mục đích chính** | Soạn thảo & biên tập Markdown trực tuyến | Môi trường phát triển tích hợp (IDE) chuyên sâu |
| **Hỗ trợ Code** | Hỗ trợ xem trước Markdown thời gian thực | Hỗ trợ chạy mã, debug đa ngôn ngữ (Python, JS,...) |
| Khả năng mở rộng | Cơ bản, tập trung vào viết tài liệu | Cực kỳ mạnh mẽ với hệ thống Extension phong phú |

3. Task List kiểm tra tiến độ cài đặt môi trường
   [x] Tải và cài đặt phần mềm VS Code phiên bản mới nhất
   [x] Cài đặt extension Python và GitLens[x] Cấu hình phím tắt và giao diện cá nhân
   [ ] Tạo repository đầu tiên trên GitHub và kết nối với máy tính
   [ ] Chạy thành công đoạn mã Python kiểm tra hệ thống đầu tiên
