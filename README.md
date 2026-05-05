# 🚀 HC-SR05 Distance Measurement (STM32)

## 🛠 Yêu cầu

* STM32CubeIDE **hoặc** Keil MDK-ARM
* Driver STM32 HAL

---

## ▶️ Cách mở project

### 🔹 Cách 1: Dùng STM32CubeIDE

1. Mở STM32CubeIDE
2. Chọn **File → Open Projects from File System**
3. Chọn thư mục project đã clone về
4. Nhấn **Finish**
5. Build và Run

---

### 🔹 Cách 2: Dùng Keil

1. Mở Keil uVision
2. Vào thư mục `MDK-ARM/`
3. Mở file `.uvprojx`
4. Nhấn **Build** → **Run**

---

## 📂 Cấu trúc project

* `Core/`: Source code chính
* `Drivers/`: Thư viện HAL
* `MDK-ARM/`: Project Keil
* `.ioc`: File cấu hình STM32CubeMX

---

## 📡 Chức năng

* Đo khoảng cách bằng cảm biến HC-SR05:
  - Chia màn hình TFT thành 2 phần đen và trắng
  - Vật cản được biểu diễn bằng điểm đỏ trên màn hình; nếu vật cản đi qua vùng đen thì đèn led sẽ sáng -> báo hiệu gặp vật cản
  
Link demo sản phẩm: https://drive.google.com/drive/folders/1Zpp4hTj9IwfCK0EUPHD0y_W50z1ezpol?usp=sharing


