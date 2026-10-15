# Bài 3: Onboarding lập trình viên mới

## 1. Mục tiêu

-   Sử dụng Inline Code để trình bày tên biến và câu lệnh ngắn.
    
-   Sử dụng Code Block có Syntax Highlighting để hiển thị mã Python.
    
-   Sử dụng Table để so sánh StackEdit và VS Code.
    
-   Sử dụng Task List để theo dõi tiến độ cài đặt.
    
-   Phân biệt văn bản Markdown ban đầu và giao diện sau khi render.
    

## 2. Hướng dẫn cài đặt VS Code

### Bước 1: Tải và cài đặt

Truy cập trang chủ [Visual Studio Code](https://code.visualstudio.com/) để tải phiên bản phù hợp với hệ điều hành. Mở tệp cài đặt và làm theo hướng dẫn.

### Bước 2: Mở Terminal

Sau khi cài đặt, mở Terminal trong VS Code bằng tổ hợp phím `Ctrl + `` hoặc chọn **Terminal → New Terminal**.

### Bước 3: Kiểm tra cài đặt

Nhập lệnh sau vào Terminal:

```
code --version
```

Nếu Terminal hiển thị số phiên bản, có thể sử dụng lệnh `code` để mở VS Code từ dòng lệnh. Nếu chưa nhận diện được lệnh, hãy kiểm tra lại cài đặt hoặc khởi động lại Terminal.

### Bước 4: Kiểm tra Python

Nếu đã cài Python, nhập lệnh sau để kiểm tra:

```
python --version
```

Nếu máy chưa có Python, cần cài đặt riêng và kiểm tra lại sau khi cài xong.

## 3. Ví dụ sử dụng Inline Code và Code Block

Inline Code dùng để trình bày các thành phần ngắn như biến `student_name`, biến `age` hoặc lệnh `print()` ngay trong đoạn văn.

Ví dụ, biến `student_name` lưu tên sinh viên, còn biến `age` lưu tuổi.

Code Block phù hợp với đoạn mã dài hơn. Khi chỉ định ngôn ngữ `python`, trình soạn thảo có thể hiển thị màu cú pháp.

```
student_name = "Vo Xuan Thinh"
age = 18

def introduce(name, age):
    print(f"Xin chao, toi ten la {name}.")
    print(f"Toi {age} tuoi.")

introduce(student_name, age)
```

Trong ví dụ trên, `student_name` và `age` là biến; `introduce()` là hàm dùng để giới thiệu thông tin sinh viên.

## 4. Bảng so sánh StackEdit và VS Code
|Tiêu chí|StackEdit|VS Code|  
|--|--|--|
|Cách sử dụng  |Trực tiếp trên trình duyệt|Cài đặt trên máy tính|
|Viết Markdown|Hỗ trợ trực tiếp|Hỗ trợ qua tính năng Preview|
|Viết code|Cơ bản|Nhiều tính năng lập trình|
|Ưu điểm|Dễ sử dụng, không cần cài đặt|Có nhiều tiện ích mở rộng|
|Hạn chế|Phụ thuộc trình duyệt|Cần cài đặt phần mềm|
|Phù hợp|Viết tài liệu, ghi chú|Lập trình, quản lý dự án|

## 5. Danh sách công việc cài đặt

- [x] Truy cập trang chủ VS Code.
    
- [x] Tìm hiểu các bước cài đặt.
    
- [ ]   Cài đặt VS Code trên máy tính.
    
- [ ]  Mở Terminal và kiểm tra lệnh `code --version`.
    
- [ ]  Kiểm tra Python nếu cần thực hành lập trình.
    
- [ ]   Thử viết và xem trước một tệp Markdown

## 6. Xử lý ký tự đặc biệt bằng Escape

Trong Markdown, một số ký tự có chức năng định dạng. Muốn hiển thị chúng như văn bản thông thường, có thể thêm dấu gạch chéo ngược `\` phía trước.

Ví dụ:

-   `\*` hiển thị ký tự * thay vì bắt đầu định dạng in nghiêng.
    
-   `\#` hiển thị ký tự # thay vì tạo tiêu đề.
    
-   `\` là ký tự Escape dùng để vô hiệu hóa chức năng Markdown của một số ký tự đặc biệt.
    

Lưu ý: Dấu Escape chỉ tác động đến ký tự phù hợp; không phải lúc nào thêm `\` cũng tạo ra kết quả giống nhau trong mọi ngữ cảnh.

## 7. Phân tích Input/Output

**Input (đầu vào):**

-   Văn bản thô được viết bằng cú pháp Markdown.
    
-   Các ký hiệu như `#`, `*`, dấu gạch đầu dòng và dấu gạch đứng `|`.
    
-   Các đoạn mã được đặt trong dấu backtick.
    
-   Tên ngôn ngữ như `python` hoặc `powershell` sau dấu mở Code Block.
    

**Output (đầu ra):**

-   Tiêu đề được hiển thị theo cấp độ.
    
-   Văn bản được in đậm, in nghiêng hoặc trình bày thành danh sách.
    
-   Câu lệnh ngắn hiển thị bằng Inline Code.
    
-   Mã Python được trình bày trong khung code và có thể có màu cú pháp.
    
-   Dữ liệu được sắp xếp thành bảng.
    
-   Công việc được hiển thị dưới dạng danh sách có ô đánh dấu.
    

**Kết quả mong đợi:** Tài liệu sau khi render trên StackEdit dễ đọc, có bố cục rõ ràng và phân biệt được phần giải thích với các câu lệnh cần nhập vào Terminal.|  
