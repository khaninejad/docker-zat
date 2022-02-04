# docker-zat
Dockerized Zendesk Apps Development Tool (ZAT)

Read more about the Zendesk App Tools: https://developer.zendesk.com/apps/docs/agent/tools

Just 
1. `docker build -t zat .`
2. `docker run --rm -it -v pwd:/data  -p 4567:4567/tcp --publish-all=true zat:latest bash`
