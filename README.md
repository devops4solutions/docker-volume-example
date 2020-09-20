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


# Youtube Link
https://youtu.be/evkgrnPy3HY

# Blog Link
https://devops4solutions.com/docker-volumes-how-to-manage-data-in-docker/
