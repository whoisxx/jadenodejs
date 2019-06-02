# jadenodjs

This is simple web server project using Nodejs, Docker and AWS

1. Docker concept : https://whoisxx.github.io/devops/about-docker/
(try to write everything I learned from this project on my tech blog)

HowTo
1. make `.dockerignore` file and write same like below
```
node_modules
npm-debug.log
```

2. build image 
```
$ docker build -t <your username>/node-web-app .
```

3. run image
```
$ docker run -p 49160:8080 -d <your username>/node-web-app --name DockerNode
```

4. test
```
$ curl -i localhost:49160
```

reference 
* https://nodejs.org/ko/docs/guides/nodejs-docker-webapp/


