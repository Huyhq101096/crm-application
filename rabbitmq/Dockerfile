# build image for rabbitmq
# step1: create DockerfileRabbit file
FROM rabbitmq:latest

# Bật plugin rabbitmq_management và rabbitmq_prometheus khi container khởi động
RUN rabbitmq-plugins enable --offline rabbitmq_management && \
    rabbitmq-plugins enable --offline rabbitmq_prometheus

# Cấu hình Docker entrypoint
ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["rabbitmq-server"]
# step2: build image in docker-compose.yml file
#   comment image: rabbitmq:latest
#   build:
#     dockerfile: ./DockerfileRabbit