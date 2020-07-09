# # Make a sample Gitlab CI pipeline to run tests every commit for a basic node js project

- Set up a free account on gitlab.com

- Make a sample app - using this as a guide https://expressjs.com/en/starter/generator.html - but basically one command `npx express-generator` (attached tar.gz is that output)

- Commit it to a fresh git project and push to gitlab.com as a new project

- Make new project public

- Then make a .gitlab-ci.yml file to make a new pipeline.



## CI Pipeline Requirements:

- must run 2 stages - test stage and archive stage
- test stage must run `npm test` and fail if tests fail

- archive stage must npm pack and allow the tar.gz result to be downloaded as an artifact.



### It will require understanding gitlab-ci, the yaml file syntax, docker images and git.
