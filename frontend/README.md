# Frontend CI/CD to AWS Elastic Beanstalk

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

It consist on a containerized  dummy frontend - using Docker - that gets tested everytime there is a PR created (or there is a push to the PR), 
and gets deployed to AWS Elastic Beanstalk everytime there is a push to master. The automation is done through Github Actions.