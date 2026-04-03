https://pkg.jenkins.io/debian-stable/
docker run -p 8080:80 mon_image

docker exec -it <container_id> sh
ls /usr/share/nginx/html
docker build --no-cache -t mon_image .
-v ./site:/usr/share/nginx/html
docker exec -it <id> sh
cat /usr/share/nginx/html/index.html

