# Домашнее задание к занятию «Запуск приложений в K8S» Соловьев Д.В.
1. [Deployment manifest файл](./kubernetes%20manifests/deployment.yaml)  
   Deployment запущен:  
   ![get pods](./pictures/get%20pods.PNG)  
   Количество реплик увеличено до 2-х:  
   ![scale](./pictures/scale.PNG)  
   [Service manifest файл](./kubernetes%20manifests/service.yml)  
   Выполнение curl из дополнительного пода:  
   ![curl](./pictures/curl.PNG)  
2. [Deployment manifest файл](./kubernetes%20manifests/deployment%202.yaml)  
   Не стартующий из-за init контейнера nginx:  
   ![get pods 2](./pictures/get%20pods%202.PNG)  
   [Service manifest файл](./kubernetes%20manifests/service%202.yml)  
   Запущенный сервис и стартовавший после этого nginx:  
   ![get pods 3](./pictures/get%20pods%203.PNG)