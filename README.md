# sample docker application

# Building
Build and run:
```
docker build -t welcome-app . 
docker run -d -p 8088:80 --name welcome-cont welcome-app
```
Open `http://localhost:8088` in your browser.
