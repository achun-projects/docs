# 安装RabbitMQ

安装docker，已安装可略过
snap install docker




docker run -d -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management