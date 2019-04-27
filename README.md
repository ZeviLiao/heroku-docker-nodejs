# heroku-docker-nodejs


local test
```
yarn
yarn start
```

deploy
```
heroku container:login
heroku container:release web
heroku container:push web
```

docker command:
```
docker images
docker ps
```
code base:  
https://github.com/heroku/docker-nodejs-hello-world

ref:  
https://blog.risingstack.com/node-hero-deploy-node-js-heroku-docker/

- windows version.
delete all images.  
https://gist.github.com/daredude/045910c5a715c02a3d06362830d045b6

stop all containers.  
https://stackoverflow.com/questions/48813286/stop-all-docker-containers-at-once-on-windows

demo site  
https://zdemo01.herokuapp.com/
