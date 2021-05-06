# docker swarm app

https://docs.docker.com/engine/install/ubuntu/ 
git clone https://github.com/sfsu-csc-667-sp-2021/swarm-app-final.git
cd swarm-app-final
sudo docker swarm init
sudo docker-compose -f devops/docker-compose.yml pull 
sudo docker stack deploy -c devops/docker-compose.yml message-app