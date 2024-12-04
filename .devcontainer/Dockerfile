# Sử dụng hình ảnh chính thức của Ubuntu
FROM ubuntu:22.04

# Cài đặt OpenJDK 8 với apt-get
RUN apt-get update && \
    apt-get install -y openjdk-21-jdk && \
    apt install -y iproute2 && \
    apt install -y wget && \
    apt install -y net-tools && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

# Các lệnh khác nếu cần
# ...

# Ví dụ: Tạo thư mục và di chuyển vào đó
WORKDIR /purpur

# Copy các tệp và thư mục cần thiết vào container (nếu cần)
# COPY ./your-application.jar /app/your-application.jar

# Các lệnh khác nếu cần
# ...

# CMD để chạy ứng dụng hoặc lệnh mặc định khi container được khởi chạy
# CMD ["java", "-jar", "/purpur/server.jar"]
