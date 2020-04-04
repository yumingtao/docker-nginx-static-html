# Description
Using nginx hosts some simple static content.

# How to build and test
- $cd root directory
- $docker build -t nginx-static .
- $docker run --name nginx-static -d -p 8081:80 nginx-static
- check http://localhost:8081/helloworld.html in web browser

# Reference
- https://hub.docker.com/_/nginx