# dockerProject
docker run -it ubuntu
docker ps
docker ps -a
docker build -t flask-docker-app .
docker run -p 5000:5000 flask-docker-app
docker run -p 5000:5000 -e APP_MESSAGE="Hello from Shahd!" flask-docker-app
docker-compose up --build
docker-compose up -d --build
docker exec -it flask_web bash
apt update && apt install -y postgresql-client
psql -h db -U myuser -d mydb
docker login
docker push shahdsamir/nginx-palestine


