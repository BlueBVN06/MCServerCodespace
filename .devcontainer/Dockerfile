FROM openjdk:8-jre

# Tạo một thư mục để chứa server Minecraft
WORKDIR /minecraft-server

# Download và chạy server Minecraft
RUN wget https://papermc.io/api/v2/projects/paper/versions/1.17/builds/392/downloads/paper-1.17-392.jar -O server.jar

# Chạy server khi Codespace được khởi động
CMD ["java", "-Xmx8G", "-jar", "server.jar"]
