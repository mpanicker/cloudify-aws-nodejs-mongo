# cloudify-aws-nodejs-mongo
A TOSCA blueprint to install a Node JS app with Mongo DB on a linux vm on AWS
1. create a zip file of the folder with the contents(there should be a upper level folder)
2. go to the Cloudify manager and click on "blue prints" and upload blue prints
3. choose the zip file and enter following params
  a. image id: ami-6d1c2007
  b. instance type: t2.micro
  c. agent user : centos
  d. web server port: 8080
4. click on deployments and execute workflow and select "install"


