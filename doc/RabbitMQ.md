# 拉取镜像
docker pull rabbitmq:3.8.9-management

# 启动rabbitmq
docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 -e RABBITMQ_DEFAULT_USER=guest -e RABBITMQ_DEFAULT_PASS=guest rabbitmq:3.8.9-management