Создал  файл docker-compose.yml в котором определены следующие сервисы:
два экземпляра nginx:alpine
prometheus для сбора метрик
grafana для визуализации метрик
node-exporter для сбора и интерпритации системных метрик
nginx-exporter для сбора и интерпритации метрик nginx
blackbox-exporter blackbox-exporter метрик связанных с сетевыми взаимодейтвиями
alertmanager для алертов в телеграм

Дашборд для визуализации get запроса на ya.ru
![image](https://github.com/user-attachments/assets/364a1256-f5ff-441b-8554-87e5a8168c65)

Дашбоард для визуализации системных ресурсов
![image](https://github.com/user-attachments/assets/871c0c82-8af4-4490-845e-5abe6c01324a)

Дашбоард для мониторинга состояния nginx, один из контейнеров остановлен
![image](https://github.com/user-attachments/assets/b182c727-8530-4950-a5d7-dccde7bfdd52)
