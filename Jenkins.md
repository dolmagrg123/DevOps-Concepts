# Jenkins

Jenkins is an open-source automation tool written in Java with plugin built for DevOps purposes. It can trigger a built for any change in the repository. It allows CI/Ci in any platform.

It supports thousands of plugins. You can also develop additional plugins in case you want. 

It increases developer productivity by automating mandatory processes. 

## How does Jenkins Work?

Plugin allow the various DevOps tools to work in Jenkins. 

## Jenkins Architecture


Jenkins uses **Master** and **Slave** architecture. The master and slave communicate through TCP/IP in this case.

Jenkins Master: pull the SCM repository, schedule build jobs, dispatch builds to the slaves for the actual execution , monitor the slaves, record and present the built results.

Jenkins Slave: It is a java executable that runs on a remote machine. Slave Jenkins instances accept requests from the Jenkins master instance and execute the job and report back the status of the master. 


## CI/CD

"Continuous Integration is the practice, in software engineering, of merging all developer working copies to a shared mainline several times a day

Continous delivery is a software engineering approach in which teams produce software in short cycle ensuring that the software can be reliably released at any time. It aims at building, testing and releasing software faster and more frequently."-Wikipedia

## Benefits

#### Reduced risk
Detect bugs early and avoid last minute risk

#### Increased confidence
As new changes are introduced, team can confiedently integrate these changes

#### Better quality
Faster tracking of bugs result in better quality

#### Ready to ship code

#### Systematic versioning

#### Code quality trend analysis
Are build taking longer? Are there less or more build fails?

#### Time to market
Since most of build test and deployments are automated, it is faster time to market

#### Reduced Cost


