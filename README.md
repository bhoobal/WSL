# WSL
Windows sub system for linux

Docker deamon connection issues:

docker ps
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?

echo "export DOCKER_HOST=tcp://localhost:2375" >> ~/.bashrc && source ~/.bashrc

root@CIRL23LKVT0B9:~# printenv | grep DOCKER
DOCKER_HOST=tcp://localhost:2375

