# Sử dụng image Redis chính thức
FROM redis:latest

# Sao chép file redis.conf từ thư mục hiện tại vào container
COPY redis.conf /usr/local/etc/redis/redis.conf

# Chỉ định lệnh khởi chạy Redis với cấu hình tùy chỉnh
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
