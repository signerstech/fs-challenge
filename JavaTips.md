# Java Tips for the ERC20 Balance Checker challenge

Here you can find some helpful tips regarding Java and serverless!

1. If using JAVA (maven), use the following command to initialize the project:
    serverless create --template aws-java-maven --name projectName
2. Heads up! Remember to update the artifactId and name properties in the project's pom file. In addition, the serverless.yaml file that was created shall be set with the role the lambda function to deploy will have. The package name has to be updated as well. If using CloudFormation for the deployment, the deploymentRole and deploymentBucket shall also be set. 
3. Once you have finished coding and you're ready to go, compile the project and use the serverless deploy command:
    serverless deploy -s dev -v

    It will use the deployment profile set on your .env file (PROFILE property).

Finally, this is the link to the web3j JAVA library, which may be used to connect to the Etherum Blockchain: 
https://github.com/web3j/web3j

You will need to import both the core and crypto artifacts. We highly recommend you to use the 4.8.7 version.