Создал  файл docker-compose.yml в котором определены следующие сервисы:
два экземпляра nginx:alpine
prometheus для сбора метрик
grafana для визуализации метрик
node-exporte для сбора и интерпритации системных метрик
nginx-exporter для сбора и интерпритации метрик nginx
blackbox-exporter blackbox-exporter метрик связанных с сетевыми взаимодейтвиями
alertmanager для алертов в телеграм

Дашборд для визуализации гет запроса на ya.ru
![image](https://github.com/user-attachments/assets/364a1256-f5ff-441b-8554-87e5a8168c65)

