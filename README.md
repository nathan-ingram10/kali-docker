
git clone https://github.com/nathan-ingram10/kali-docker.git

cd docker-image

docker build -t kali-mini-os .

docker ps -a

docker image ls

docker run -it kali-mini-os
