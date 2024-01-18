# StudentPerformance
876805237062.dkr.ecr.us-east-1.amazonaws.com/studentsperformance

# Docker setup in EC2
sudo apt-get update -y
sudo apt-get upgrade

# Requuired
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu 
newgrp docker
