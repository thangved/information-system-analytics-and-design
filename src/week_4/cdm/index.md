---
marp: true
_class: lead
paginate: true
header: Phân tích thiết kế hệ thống thông tin - Nhóm 1
footer: Created by Minh Thang with **marpit**
---

![bg left](./assets/Conceptual-Data-Model.jpg)

# **Mô hình dữ liệu mức quan niệm**

(Conceptual Data Model)

---

## **Nội dung**

1. Mô hình dữ liệu mức quan niệm
1. Một số khái niệm
1. Các bước xây dựng CDM

---

## **Mô hình dữ liệu mức quan niệm (Conceptual Data Model)**

- Mô hình dữ liệu mức quan niệm là mức trừu tượng cao nhất trong việc biểu diễn nhu cầu thông tin của một tổ chức.

---

## **Một số khái niệm**

- Thực thể, kiểu thực thể và thể hiện của kiểu thực thể
- Thuộc tính
- Khóa của thực thể
- Quan hệ (Relationship)
- Bậc của quan hệ
- Bản số trong quan hệ
- Tổng quát hóa / chuyên biệt hóa

---

## **Một số khái niệm**

### Thực thể (Entity)

- Một thực thể (Entity) là một con người, một nơi, một đối tượng, một sự kiện hay một khái niệm trong môi trường người dùng mà tổ chức đó muốn duy trì dữ liệu
- Kiểu thực thể (Entity type) là tập hợp các thực thể có cùng đặc điểm và tính chất
- Thể hiện của thực thể (Entity instance) là một hiện thực của một kiểu thực thể

---

## **Một số khái niệm**

### Thuộc tính (Attribute)

- Thuộc tính (attribute) mô tả một tính chất hay đặc điểm của một kiểu thực thể
- Miền trị của thuộc tính (attribute domain) là tập các giá trị có thể gán được cho một thuộc tính

---

## **Một số khái niệm**

### Khóa của thực thể (Entity key)

- Khóa của thực thể là một hay một tập các thuộc tính của thực thể mà giá trị của nó có thể xác định được duy nhất một thể hiện của một kiểu thực thể

---

## **Một số khái niệm**

### Quan hệ (Relationship)

- Quan hệ là một sự kết hợp giữa các thể hiện của một hay nhiều kiểu thực thể mà nó có liên quan với nhau
- Bậc của quan hệ (Degree): là số kiểu thực thể tham gia vào quan hệ
- Quan hệ một ngôi là quan hệ chỉ có một kiểu thực thể (bậc 1)

---

## **Một số khái niệm**

### Bản số (Cadinality)

- Bản số của thực thể A trong mối kết hợp với kiểu thực thể B là số thể hiện của kiểu thực thể B có thể kết hợp với mỗi thể hiện của kiểu thực thể A

---

## **Một số khái niệm**

### Tổng quát hóa - chuyên biệt hóa

- Chuyên biệt hóa (specialization) là phân hoạch một thực thể thành các tập con, còn tổng quát hóa (generalization) là gộp các thực thể con thành một thực thể bao hàm tất cả các thể hiện của các thực thể con.

---

## **Các bước xây dựng CDM**

- Bước 1: Xác định các kiểu thực thể
- Bước 2: Xác định các kiểu quan hệ và bản số
- Bước 3: Xác định các thuộc tính và miền giá trị
- Bước 4: Xác định các khóa ứng viên và khóa chính
- Bước 5: Xác định tổng quát hóa / chuyên biệt hóa các thực thể (nếu có)
- Bước 6: Vẽ sơ đồ E-R
- Bước 7: Kiểm tra lại ERD
