# static-website-01
commands:
```
docker build -t mbidzinsk/static-website-01:latest .
docker run --name static-website --publish 7080:80 mbidzinsk/static-website-01:latest 
docker push mbidzinsk/static-website-01
```