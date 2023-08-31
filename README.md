# django-docker

cd cool_counters

sudo docker build -t djangoapps:v1 .

sudo docker run -it djangoapp:v1

[ copy the container id after executing below command ]
sudo docker ps -a 

docker exec -it container_id bash 


