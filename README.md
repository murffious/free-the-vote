<h1 align="center">My-Constitution-Vote</h1>
  
- Recommend "to vote for who" system to recommend votes based on data mining/social media and Representatives/Candates activity like votes and such. aka Rock My Vote feature.

- Also using AI to give a score to each candidate based on constitutional principles.

- Seek to get Candidates to endorse it to bring validity and also hold them accountable to the general easy acceile public and not just the news sites. 

## Tech stack 
Node React or Angular with Azure ML or AWS ML and Creative Tim Themes 

## Documentation

Check out our [documentation website](https://kards.dev/rockmyvote).

## Contributing

Read our [contributing guide](/CONTRIBUTING.md) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to the app.

Notice that contributions go far beyond pull requests and commits.
Although we love giving you the opportunity to put your stamp on RockMyVote, we also are thrilled to receive a variety of contributions. Data needs. 

## Who sponsors RockMyVote?
- Morf Tech 

### Gold 🏆

Diamond Sponsors are those who have pledged $100/month or more to RockMyVote.
via [OpenCollective](https://opencollective.com/rockmyvote)

## Changelog

Please read the [changelog](https://kards.dev/rockmyvote/releases).

## Roadmap

The future plans and high priority features and enhancements can be found in the [roadmap](https://kards.dev/rockmyvote/roadmap/) file.

## License

This project is licensed under the terms of the
[MIT license](/LICENSE).


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

