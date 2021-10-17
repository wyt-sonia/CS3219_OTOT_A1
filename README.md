# CS3219 OTOT A1

steps:

- cd nginx
- docker build -t myapp:latest .
- cd ../proxy
- docker build -t myproxy:latest .
- cd ..
- docker-compose up -d   
- then go to brower and visit: localhost:8080, where you can see the nginx welcome page
