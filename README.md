# Задание: 

Используйте Spring Actuator для отслеживания метрик вашего приложения. Настройте визуализацию этих метрик с использованием Prometheus и Grafana.

- Добавил зависимости в pom.xml в два микросервиса
- Добавил в файл конфигурации метрики, которые будем собирать
- Произвел настройку конфигурационного файла Prometheus
- Ввиду отстутствия возможности установить Grafana, поднял докер контейнер на виртуальной машине Ubuntu
  ```
  docker run -d --name=grafana -p 3000:3000 grafana/grafana-enterprise:11.4.0-ubuntu
  ```
- Проверил подключение микросервисов к Prometheus
- Настроил связь между Prometheus и Grafana
- Посмотрел графическое отображение метрик

  По каждому шагу приложил скриншот
