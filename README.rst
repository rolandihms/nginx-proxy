1. mkdir nginx-proxy
2. git init
3. git remote add origin https://github.com/rolandihms/nginx-proxy.git
4. git pull origin master

5. Create directories
	- bash setup.sh
6. Create Docker Network
	- docker network create nginx-proxy

7. docker-compose up -d

Thats it reverse proxy up. Go and add docker apps to the nginx-proxy network