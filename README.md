# Mô tả công việc tại mht

## 1. Mô tả chung
### 1.1 Thiết kế phần cứng
  * 1.1.1 Yêu cầu cơ bản
    * Thiết kế mạch bằng các công cụ phổ biến: altium, kicad
    * Đọc hiểu datasheet, reference design
    * Phân tích thiết kế tối ưu không gian vỏ hộp, tối ưu giá thành

  * 1.1.2 Yêu cầu nâng cao
    * Thiết kế mạch nguồn: Tính toán cho các mạch nguồn switching phổ biến
    * Thiết kế các mạch high speed: Chủ yếu cho các ngoại vi các boad embedded-linux: USB, sdcard, ethernet, nand nor memory bus
    * Thiết kế các mạch RF: tính toán phối hợp trở kháng antenna cho các mạch bluetooth, zigbee

### 1.2 Lập trình MCU
  * 1.2.1 Yêu cầu cơ bản
    * Có kinh nghiệm làm việc với MCU 8, 32 bit và các ngoại vi phổ biến: UART, SPI, I2C, I2S, ...
    * Có kinh nghiệm làm việc với các sensor phổ biến.
    * Có kinh nghiệm làm việc trên các IDE phổ biến: eclipse, VsCode, IAR

    * Có kinh nghiệm làm việc với các RTOS framework phổ biến: FreeRTOS, Chibi-RTOS, TI-RTOS, Micrium, ...

  * 1.2.2 Yêu cầu nâng cao

    * Có kinh nghiệm porting các opensource-framework phổ biến vào project
    * Có kinh nghiệm làm việc và chuyển đổi qua lại với nhiều loại compiler: gcc, iar, TI-CGT, ...
    * Có kinh nghiệm làm việc với các protocol phổ biến trên MCU: TCP-IP, zigbee, bluetooth, homekit, z-wave, rs-485, modbus, ...

### 1.3 Thiết kế test tool
  * 1.3.1 Yêu cầu cơ bản
    * Thiết kế các tool bằng C, Python, javascript(nodejs), bash, trên các board embedded-linux.
    * Có kinh nghiệm làm việc với các ngoại vi của các board embedded-linux.

  * 1.3.2 Yêu cầu nâng cao
    * Có kinh nghiệm làm việc với linux-kernel để can thiệp sử dụng hoặc can thiệp driver.
### 1.4 Lập trình phần mềm phía back-end
  * 1.4.1 Yêu cầu cơ bản
    * Thiết kế các ứng dụng giao tiếp và quản lý nhiều node trong mạng multi-protocol: zigbee, bluetooth, homekit, z-wave
    * Cung cấp giao diện cho front-end và kết nối cloud
    * Có kinh nghiệm làm việc với C, Python, javascript(nodejs)

  * 1.4.2 Yêu cầu nâng cao
    * Có kiến thức về linux-systemd để thiết kế các service cho ứng dụng
    * Có kinh nghiệm làm việc với các cloud service: aws-lambda, google-action
    * Phân tích thiết kế tối ưu cho mô hình mạng multi-node

### 1.5 Lập trình phần mềm phía front-end
  * 1.5.1 Yêu cầu cơ bản
    * Framework: react-js
    * Thiết kế web-app giao tiếp với back-end và cloud
    * Thiết kế mobile-app giao tiếp với back-end và cloud

  * 1.5.1 Yêu cầu nâng cao
    * Thiết kế các chức năng cho ứng dụng dựa trên mô hình mạng sẵn có của back-end để cải thiện UI-UX

### 1.6 Quản trị và vận hành cloud
  * 1.6.1 Yêu cầu cơ bản
    * Làm việc với các cloud-service phổ biến: aws, gcp, azure, ...
    * Vận hành và xử lý sự cố

## 2. Phân loại:
### 2.1 Thiết kế phần cứng và backend
  * 1.1 + 1.2 + 1.3 + 1.4
### 2.1 Thiết kế phần mềm và backend
  * 1.4 + 1.5 + 1.6