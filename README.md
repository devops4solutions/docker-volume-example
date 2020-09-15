# docker-volume-example

# Named Volume

```
cd Named-Volume
docker-compose -up d

```



# Populate volume using a container


```
docker run -d \
  --name=nginxtest \
  -v nginx-vol:/usr/share/nginx/html \
  nginx:latest
```
