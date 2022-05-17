# node-eb-example
https://medium.com/avmconsulting-blog/how-to-deploy-a-node-app-on-aws-elastic-beanstalk-with-docker-9664e5841fe


npm init --yes
npm add express
touch index.js
node index
docker build --tag=node-docker-eb .
docker run -p 80:3000 node-docker-eb
docker build --tag omegabloods/node-docker-eb .