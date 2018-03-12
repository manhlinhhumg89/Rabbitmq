# Rabbitmq
* Cai RabbitMq 
- Cài đặt docker bằng package `https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-from-a-package`.
- docker pull rabbitmq:3.6.14-management-alpine
- docker run -d -it --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.6.14-management-alpine
- amqp://test:test@localhost:5672/demo-rabbitmq(mở trình vào địa chỉ localhost://15672 là giao diện của rabbitmq)
* Tiến hành chạy ở file
- phải run rabbitmq bằng docker: docker start rabbitmq 
- chạy file app8.js trước sau đó chạy tiếp app9.js
- Thấy 2 file 1 là gửi và 1 là nhận kết quả. => Cách hoạt động của Rabbitmq

