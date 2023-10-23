https://topdev.vn/blog/apache-kafka-la-gi/

# Structure

![Alt text](image.png)

![Alt text](image-1.png)

![Alt text](image-2.png)

# Concept

[1] Producer: Một producer có thể là bất kì ứng dụng nào có chức năng publish
message vào một topic. [2] Messages: Messages đơn thuần là byte array và
developer có thể sử dụng chúng để lưu bất kì object với bất kì format nào –
thông thường là String, JSON và Avro [3] Topic: Một topic là một category hoặc
feed name nơi mà record được publish. [4] Partitions: Các topic được chia nhỏ
vào các đoạn khác nhau, các đoạn này được gọi là partition Consumer: Một
consumer có thể là bất kì ứng dụng nào có chức năng subscribe vào một topic và
tiêu thụ các tin nhắn. [5] Broker (là một server lưu trữ các topic): Kafka
cluster là một set các server, mỗi một set này được gọi là 1 broker Zookeeper:
được dùng để quản lý và bố trí các broker.

-> Kafka tên đầy đủ là Apache Kafka. Là một nền tẳng Streaming phân tán sự kiện
(distributed event streaming) chủ yếu được áp dụng làm hệ thống phân tán, vận
chuyển tin nhắn và thu thập, xử lý, lưu trữ, và phân tích dữ liệu ở quy mô lớn.

# Reference

https://blog.logrocket.com/microservices-nestjs-kafka-typescript/

# Expend

[1] Event Streaming: [2] Lưu trữ dữ liệu: kafka lưu trữ message thậm chí sau khi
đã gửi đi để phòng tránh bị mất dữ liệu. Dữ liệu đó có thể re-consumed,
re-subscribe lại message khoải mái theo yêu cầu.

# Study Kafka

https://www.youtube.com/watch?v=_mw5QupT4ts
