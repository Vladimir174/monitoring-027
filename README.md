**Конфигурации Grafana Loki**
Домашнее задание
Конфигурации Grafana Loki

**Цель:**
Заменить Elasticsearch на Grafana Loki.


Описание/Пошаговая инструкция выполнения домашнего задания:
В данном ДЗ вы можете воспользоваться наработками из предыдущего.

В данном ДЗ вам предстоит заменить Elasticsearch на Grafana Loki. Убедитесь, что данные поступают в Grafana Loki и к ним есть доступ.

В качестве результата ДЗ принимаются - файл конфигурации Grafana Loki, файл конфигурации шиппера логов (любой шиппер на ваш выбор), скриншот, в котором видно, что вы получили доступ к логам в Grafana Loki.

___________________________________________________

В контейнерах подняты loki, используется grafana из предыдущих занятий и контейнер с promtail.

![image](https://github.com/user-attachments/assets/1d2f617c-2b2f-408c-8a46-15f65e6e7153)

Используются конфиги, которые лежат по месту. Это конфиг [promtail](https://github.com/Vladimir174/monitoring-027/blob/main/config.yml) и [docker-compose](https://github.com/Vladimir174/monitoring-027/blob/main/docker-compose.yml)

Данные из лога ngixn с ошибками

![image](https://github.com/user-attachments/assets/c1f31293-da62-4ea3-9876-fbdab3144321)


![image](https://github.com/user-attachments/assets/58c1fef4-e41a-492e-ba44-13c5da7b1770)





