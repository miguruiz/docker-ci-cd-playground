# docker-ci-cd-playground

Simple multi-project repo that contains the following projects using docker:


| projects      | description                                                                                                                                                                                                                                                                   | 
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| frontend      | It consist on a containerized  dummy frontend - using Docker - that gets tested everytime there is a PR created (or there is a push to the PR),and gets deployed to AWS Elastic Beanstalk everytime there is a push to master. The automation is done through Github Actions. |
| visitsWebsite | Small website that counts the number of visits. It uses two containers, one with the node JS app and another with redis.                                                                                                                                                      |
| simpleWeb     | A simple website that returns Hi there                                                                                                                                                                                                                                        |
| redis-image   | Just a dockerized redis                                                                                                                                                                                                                                                       |