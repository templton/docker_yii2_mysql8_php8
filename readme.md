# Обсчет стока

## Запуск сборки
 
- `cp .env.dist .env`  
- `docker-compose up --build`
- `docker exec -it api_php composer create-project --prefer-dist yiisoft/yii2-app-basic basic