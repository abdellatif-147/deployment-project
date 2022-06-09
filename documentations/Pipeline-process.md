 
# Pipeline process

### once you pushed your commits will trigger these steps:-

1- Spin up environment
``` setup and starting environment for out technology ```
2- Preparing environment variables
``` preparing all environment variables to use in AWS```
3- Install Node.js
``` install for node Js environment ```
4- Checkout code
``` to check out source code to the configured path (defaults to the working_directory). The reason this is a special step is   because it is more of a helper function designed to make checking out code easy for you. ```
5- Install AWS CLI v2
``` install to AWS CLI to can use it to run AWS commands ```
6- Disable AWS pager if not already configured
``` to Disable AWS pager if not already configured ```
7- Configure AWS Access Key ID
``` Configure AWS Access Key ID to can access your services ```
8- Configure AWS Secret Access Key
``` Configure Secret Access Key and Access Key ID to can access your services ```
9- Configure AWS default region
``` to configure your region will be use ```
10- Front-End Install
``` install all Front-End dependencies ```
11- Back-End Install
``` install all Back-End dependencies ```
12- Front-End Build
``` compile Front-End code and make a build to use it with deployment ```
13- Back-End Build
``` compile Back-End code and make a build to use it with deployment ```
14- Deploy App
``` finally you can deploy your builds on front-end & back-end ```