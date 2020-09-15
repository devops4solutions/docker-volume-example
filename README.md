# docker-volume-example

# Populate volume using a container

'''
docker run -d \
  --name=nginxtest \
  -v nginx-vol:/usr/share/nginx/html \
  nginx:latest
  '''
