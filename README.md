# Lab 16: AWS Cloud Server

## 
- [GUI deployed server](http://lab16awscloudserver-env.eba-aeygra2b.us-east-2.elasticbeanstalk.com/)
- [CLI deployed server](http://aws-cli-deployment-dev.us-west-2.elasticbeanstalk.com/)


## Processes
### GUI
1. Zip the file (NOT node modules, package-lock, or .env)
1. follow prompts on GUI to create new application
  - platform = Node.js
  - name = Lab16AwsCloudServer

### CLI
1. Zip the file (NOT node modules, package-lock, or .env)
1. `eb init` to make new app
1. `eb create` + name to set the envorinment name
1. `eb deploy` to deploy