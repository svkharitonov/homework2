#Задание #2
svk-demo2 - chart демо приложения с зависимостью postgresql version: 9.8.7 (repository: https://charts.bitnami.com/bitnami)

#Установка
helm install hw2 svk-demo2 

#Запуск тестов newman
newman run svk-hw2.postman_collection.json


