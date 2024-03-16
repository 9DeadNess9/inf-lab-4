## Установка Docker
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/599958cb-6b71-4e5e-9731-9043b6c398b3)

# Создаю образ
## Создание Dockerfile
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/f7030e14-4836-45e2-8a59-e015c0661eb4)
## Устанавливаю libaa-bin - где находится aafire и iputils-ping, чтобы делать ping
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/7dbce3f6-43ee-49c7-986b-eef2b722f179)

## Сборка образа с тегом “aafire1”
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/99d713aa-8d19-4838-9df3-a1c5e04803ea)
## Сборка образа с тегом “aafire2”
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/dda99be5-74f2-466f-9699-e443b6e2b075)

## Созданные образы и запуск aafire
### у меня запуск нескольких контейнеров съедал всю память, поэтому я использовал ограничение на логи log-opt
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/2b6f2712-6900-4f13-b1cb-486035e79b63)
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/3be6c872-ed00-49bd-b752-0c456392d3ec)

# Запуск контейнеров, создание сети, задание порта и имён у контейнеров, объединение их в сеть
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/9e07f8ff-ed94-4cc4-9237-9697c00452cd)

## Ping от fire_one к fire_two и обратно
![image](https://github.com/cs-itmo-2023/lab-4-kr4nder/assets/99131850/07ef5346-c5ab-4031-96e2-0d1dec243a9f)
