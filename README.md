Создал  файл docker-compose.yml в котором определены следующие сервисы:

два экземпляра nginx:alpine

prometheus для сбора метрик

grafana для визуализации метрик

node-exporter для сбора и интерпритации системных метрик

nginx-exporter для сбора и интерпритации метрик nginx

blackbox-exporter для сбора метрик связанных с сетевыми взаимодейтвиями

alertmanager для алертов в телеграм

Далее прилагаю скриншоты экспортированных дашбоардов

Дашборд для визуализации get запроса на ya.ru
![image](https://github.com/user-attachments/assets/364a1256-f5ff-441b-8554-87e5a8168c65)

Дашбоард для визуализации системных ресурсов
![image](https://github.com/user-attachments/assets/871c0c82-8af4-4490-845e-5abe6c01324a)

Дашбоард для мониторинга состояния nginx, один из контейнеров остановлен
![image](https://github.com/user-attachments/assets/b182c727-8530-4950-a5d7-dccde7bfdd52)


скриншот алерта при внезапном исзезновении доступа в интернет:

![image](https://github.com/user-attachments/assets/d4e55978-8fff-418f-b90c-91ae49cbd243)


скриншот алерта при остановке контейнера nginx:

![image](https://github.com/user-attachments/assets/d3447fdd-13f9-4bf6-9092-5756b6eccf3a)
