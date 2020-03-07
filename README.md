# aws-travis-production-grade-workflow
_repo that uses Docker, Nginx, Node.JS server, React, SQL Postgres, Redis Caching, CD/CI w/Travis workflows to test/host to AWS_ 
 - Push code 
 - Travis pulls repo
 - Travis builds a test image, tests code (if passing it goes on, if not it stops) 
 - Travis builds prod images
 - Travis pushed built images to Docker Hub
 - Travis pushes project to AWS Elastic Beanstalk (S3 bucket is used for the code)
 - EB pulls images from Docker Hub, deploys

*Based on code from the Docker and Kubernetes Course on Udemy by Stephen Grider

