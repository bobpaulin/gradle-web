#Gradle Web Template for Continuous Delivery

Create a properties file with your username on the machine you will be running the build on.

Example if your user name is bobpaulin you would create:

bobpaulin.properties

Within this file place the following:
    #The Repository Username
    repository_user=admin
    #The Repository Password
    repository_password=password
    #The build number
    buildInfo.build.number=1
