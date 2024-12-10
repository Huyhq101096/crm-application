redis/
│
├── docker-compose.yml          # File cấu hình Docker Compose
├── .env                        # File chứa biến môi trường
├── redis/
│   ├── redis.conf              # File cấu hình Redis
│   └── entrypoint.sh           # Script khởi động Redis (tùy chọn)
├── redis-data/                 # Thư mục lưu trữ dữ liệu Redis (volume)
└── redis-logs/                 # Thư mục lưu log Redis (volume)
