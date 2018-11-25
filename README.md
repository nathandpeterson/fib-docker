This project was built to practice using a multi-container docker deployment pipeline. On its surface, it is just a fibonacci calculator. In order to determine and communicate the fibonacci number for a given index, it uses the following services.

* Node API server
* Node worker service
* Redis
* Postgres
* Nginx
* React UI

It will be deployed to AWS Elastic Beanstalk using Travis CI and Dockerhub.

I built this following Stephen Grider's Udemy tutorial on Docker and Kubernetes:
https://www.udemy.com/docker-and-kubernetes-the-complete-guide
