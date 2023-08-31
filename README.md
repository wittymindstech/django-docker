# django-docker

cd cool_counters

sudo docker build -t djangoapps:v1 .

sudo docker run -p 12345:8000 djangoapp:v1

From another terminal ( open a new terminal to ec2 ) and  run this below command to access the django page,
and also add security group for custom tcp port 12345 to access from chrome: 

wget http://localhost:12345

[ To access the container to check files, copy the container id after executing below command ]
sudo docker ps -a 

docker exec -it container_id bash 


