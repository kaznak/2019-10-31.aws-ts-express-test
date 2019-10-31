
# 2019-10-31.aws-ts-express-test

This repository is an example of Nodejs(Javascript and Typescript) application for a CI pipeline of CodePipeline.
The target environment is assumed as a Nodejs stack of Elastic Beanstalk.

Each branch of this repository is for different types of pipelines.

+ master/express-typescript-codebuild: source-build-deploy pipeline
	- The Typescript version application requires a build phase.
+ express-javascript: source-deploy pipeline
	- Full javascript version application does not require build phase.
+ express-typescript: source-deploy pipeline
	- The Typescript version application requires a build phase.
	- This version builds while the application is starting up.
