# sample docker application

# Building
Build and run:
```
docker build -t docker-demo-app . 
docker run -d -p 8088:80 --name demo-cont docker-demo-app
```
Open `http://localhost:8088` in your browser.
