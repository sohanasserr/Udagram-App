The application reposatory is linked to Circleci, so when a code is commited/pushed to the master branch it
triggers the Circleci pipeline and a series of events gets excuted and it happens as follows:

Docker container set up
setup environment
install node.js
install aws cli
configure aws keys
install eb
install dependencies udagram-frontend
install dependencies udagram-api
build udagram-frontend
build udagram-api
deploy udagram-fronend inside s3 bucket
deploy udagram-api that live in elastic beanstalk