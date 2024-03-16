# Hệ thống app nhận diện lá cây và phân loại loại cây

## 1. Login/Register

## 2. Nhận diện lá cây và phân loại loại cây

-   Chụp ảnh hoặc chọn ảnh từ thư viện từ client
-   Đẩy ảnh từ client lên server để đưa vào model object detection để xác định vị trí lá cây, trả về client vị trí lá cây

    > Có thể để model object detection trên server hoặc client

    > Sau khi xác định vị trí lá cây, vẽ bounding box lên ảnh và hiển thị ảnh, có thế cho phép người dùng chỉnh sửa bounding box nếu cần thiết

-   Đẩy ảnh đã được bounding box lên model classification trên server để phân loại loại cây, trả về client kết quả phân loại (tên cây, tình trạng bệnh)

## 3. Hiển thị thông tin cây

- Tên cây
- Hình ảnh cây
- Mô tả cây
- Cách chăm sóc cây
- Cách sử dụng cây
- Cách phòng tránh sâu bệnh
- Cách chữa trị sâu bệnh

## 4. Lưu thông tin cây

- Lưu thông tin cây đã nhận diện vào database
- Hiển thị thông tin cây đã lưu
- Có thể xóa thông tin cây đã lưu

## 5. Thống kê

- Thống kê số lượng cây đã nhận diện theo ngày, tháng, năm

## 6. Đăng xuất


```