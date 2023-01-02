---
marp: true
theme: gaia
backgroundColor: #fff
_class: lead
paginate: true
header: Phân tích thiết kế hệ thống thông tin - Nhóm 1
footer: Created by Minh Thang with **marpjs**
style: |
  @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,300;0,500;0,700;0,900;1,100;1,300;1,500;1,700;1,900&display=swap');
  * {
    font-family: 'Raleway', sans-serif;
  }
  .row {
      display: flex;
  }
  .col {
    flex: 1;
    padding: 10px;
    align-items: center;
    text-align: center;
  }
---

![bg left:40%](./assets/images/img_1.jpg)

# **Hệ thống**

(System)

---

## Nội dung

1. Các khái niệm hệ thống
1. Đặc điểm của hệ thống
1. Các kiểu quan hệ tương tác giữa các hệ thống
1. Phân loại hệ thống
1. Các khái niệm liên quan đến hệ thống

---

## Các khái niệm hệ thống

Hệ thống là tập hợp các đối tượng, các thành phần có liên quan với nhau, tương tác với nhau theo những nguyên tắc, cơ chế nào đó cùng tồn tại trong một thể thống nhất.

:computer: **Trong khoa học máy tính (CS)** và **Khoa học thông tin (IS)**, hệ thống là một hệ thống phần mềm, trong đó gồm các thành phần như: cấu trúc hệ thống, tập hợp các phương thức cơ bản để trao đổi dữ liệu giữa các quá trình của hệ thống và cách hoạt động của hệ thống.

---

## Các khái niệm hệ thống

:fire: Tóm lại, hệ thống được hiểu là tập hợp các đối tượng có quan hệ hữu cơ với nhau, tác động chi phối lẫn nhau theo một cơ chế xác định, cùng cộng tác hoạt động theo các quy tắc nhất định để đạt được các mục tiêu đề ra.

---

### Ví dụ về hệ thống

**Hệ mặt trời** là tập hợp các vật thể thiên văn quay xung quanh mặt trời.

![width:500px](./assets/images/img_2.png)

---

### Ví dụ về hệ thống

**Hệ điều hành** là tập hợp các phần mềm hệ thống giúp quản lý tài nguyên của máy tính và cung cấp các _API_ để các ứng dụng hoặc người dùng có thể giao tiếp dễ dàng với phần cứng của máy tính.

<div class="row">
<div class="col">

![width:100px](./assets/images/Tux.svg) ![width:100px](./assets/images/ubuntu.gif)
Linux :penguin:

</div>

<div class="col">

![width:100px](./assets/images/windows.jpg)
Windows :window:

</div>

<div class="col">

![width:100px](./assets/images/mac-os.jpg)
MacOS :apple:

</div>

</div>

---

## Đặc điểm của hệ thống

Mỗi hệ thống đều có các đặc điểm sau:

- Mỗi hệ thống đều phải có cấu trúc (Structure)
- Mỗi hệ thống đều có cách hoạt động (Behavior)
- Mỗi hệ thống đều có sự kết nối bên trong (Interconnectivity)
- Cấu trúc và cách hoạt động có thể phân rã (Decomposition) thành các hệ thống con (Subsystem) và các tiến trình con (Subprocess)

---

## Các kiểu quan hệ tương tác giữa các hệ thống

- Kiểu quan hệ phân cách nhau: input -> :computer: -> output
- Kiểu quan hệ bao hàm nhau: hệ thống này là thuộc hoặc chứa hệ thống kia.
- Kiểu quan hệ giao nhau: các thành phần của hệ thống này cũng là thành phần của hệ thống khác.

---

## Phân loại hệ thống

- Hệ thống mở: là hệ thống có tính xác suất trong đó đầu vào, đầu ra không thể xác định nhưng có thể dự đoán được.
- Hệ thống đóng: là hệ thống có thể đoán trước kết quả đầu ra nếu biết đầu vào.
- Các hệ thống tự nhiên: là các hệ thống không do con người tạo ra
- Các hệ thống do con người tạo ra.

---

## Các khái niệm liên quan đến hệ thống

- Một hệ thống: một hệ thống thường bao gồm nhiều thành phần mà ta thường gọi là hệ thống con (subsystems), mỗi hệ thống con đảm nhận một tác vụ nào đó trong hệ thống lớn mà nó là thành phần.
- Môi trường: là những thứ xung quanh hệ thống bao gồm con người, phương tiện, chính sách...
- Biên hay giới hạn: là chu vi hay đường ranh giữa hệ thống với môi trường bên ngoài
  ...
