# Important DevOps Concepts

## Table of contents
* [Software Delivery Cycle](#Software-Delivery-Cycle)
* [Test Driven Development](#Test-Driven-Development)
* [Continuous Integration](#Continuous-Integration)
* [Continuous Delivery](#Continuous-Delivery)
* [Configuration Management](#Configuration-Management)
* [Containerization](#Containerization)
* [Cloud Scalability and Reliability](#Cloud-Scalability-and-Reliability)

## Software Delivery Cycle
The Software Development Life Cycle is a process that ensures good software is built. Each phase in the life cycle has its own process and deliverables that feed into the next phase. It involves all tasks involved in planning, creating, testing and deplaoying a Software Product. 

### Purpose:

SDLC process leads to the development of the software in a systematic and disciplined manner.
SDLC helps to deliver a high quality product according to the needs and demands of the customer.

### SDLC Phases

Given below are the various phases:

1. Requirement gathering and analysis
2. Design
3. Implementation or coding
4. Testing
5. Deployment
6. Maintenance

There are typically 5 phases starting with the analysis and requirements gathering and ending with the implementation. 
 
 1. Requirements Gathering/Analysis

 This is the planning stage. The project manager and the client decide all the requirements of the project. This stage is where all the relevant information is collected to develop a product that satisfies the needs of the customer. Understanding the purpose of the product is important to find out the next steps of the product.

 2. Design

 Once all the requirements are gathered in the previous steps, the next step will be to derive a software architecture that is used for implementing system development.
 
 3. Implementation

 The design of the software is used to write code to implement into the software.

4. Testing

Once the coding is completed, we need to test the code in this stage. If any errors are found, the devlopers try to fix them. After continous testing and fixing, a product is finally derived that fulfills the needs and demands of the customer.

5. Deployment

The tested product that is ready is now deployed in this stage.

6. Maintenance

Finally, when the desired product is delivered, the developers work on continous maintenance of the product if any issues come.



- Waterfall Model
- Agile Model

 [Top](#Table-of-Contents)

## Test Driven Development

Test Driven Development(TDD) is a software development approach in which test cases are developed to specify and validate what the code will do. In this approach before writing the additional code, test cases are created for each function. 
Test-Driven development is a process of developing and running automated test before actual development of the application. Hence, TDD sometimes also called as Test First Development.

### How to perform TDD Test

Following steps define how to perform TDD test,

- Add a test.
- Run all tests and see if any new test fails.
- Write some code.
- Run tests and Refactor code.
- Repeat.

1. Add a test:
Each new feature is started by writing a test that checks if the function fulfills the requirements needed. The developer can hence focus on the requirements before even writing the code itself.


2. Run all tests and see if any new test fails:
The code should pass all the test to make sure it fulfills all the requirements. Each new test will fail because the required code has not been written yet for the new test.

3. Write some code:
Now, we write the code so that the new test passes.

4. Run tests and Refactor code:
Again, we run all the test to see if the code passes them all. As the code grows, there will be continous refactoring of the code.

5. Repeat:
The above steps are repeated by starting a new test. 


### Benefits of TDD:

1. Much less debug time

2. Code proven to meet requirements

3. Tests become Safety Net

4. Near zero defects

5. Shorter development cycles

## Continuous Integration

Continous Integration is a software development practice where each member of a team integrate(commit) their work frequently. Each integration is verified by an automated build to detect integration errors as quickly as possible. 

While working in a team, if all the developers wait for days or weeks before they commit their changes, it is hard to fit the code with each other, so CI helps to make sure that all the developers commit their changes to a shared version control branch to avoid such problems.

### Benefits:

1. Significantly reduced integration problems
2. Rapid development of a cohesive software
3. Ensures bugs are caught earlier in the development cycle, which makes them less expensive to fix. 


## Continuous Delivery

Continuous delivery is a software development practice where code changes are automatically prepared for a release to production. These changes could be new features, configuration, changes, bug fixes and experiments. The goal is deploy changes/updates continously according to the demands. It aims at building, testing, and releasing software with greater speed and frequency.

### Benefits:

1. Faster time to market:

It’s not uncommon for the integration and test/fix phase of the traditional phased software delivery lifecycle to consume weeks or even months. When teams work together to automate the build and deployment, environment provisioning, and regression testing processes, developers can incorporate integration and regression testing into their daily work and completely remove these phases.

2. Higher quality:

When developers have automated tools that discover regressions within minutes, teams are freed to focus their effort on user research and higher level testing activities such as exploratory testing, usability testing, and performance and security testing.

3. Lower Costs:

Any successful software product or service will evolve significantly over the course of its lifetime. By investing in build, test, deployment and environment automation, we substantially reduce the cost of making and delivering incremental changes to software by eliminating many of the fixed costs associated with the release process.

4. Happier Teams: 

Peer-reviewed research has shown continuous delivery makes releases less painful and reduces team burnout. Furthermore, when we release more frequently, software delivery teams can engage more actively with users, learn which ideas work and which don’t, and see first-hand the outcomes of the work they have done. 




## Configuration Management

Configuration Management is an automated method to maintan consistency in the product's performance, functional and physical. Configuration management is important because it enables the ability to scale infrastructure and software systems without having to correspondingly scale administrative staff to manage those systems. 

It is common for configuration management tools to include automation too. Popular tools are:

- Red Hat Ansible
- Chef
- Puppet

## Containerization

Containerization is a process of encapsulating or packing up software code and all its dependencies so that it can run uniformly and consistently on any infrastructure. 

With this process developers can create and deploy their applications faster and more securely as the computing environment no longer plays a big role in error or bugs.

### Benefits

1. Portability
2. Agility
3. Speed
4. Fault isolation
5. Ease of management

## Cloud Scalability and Reliability

Cloud Scalability is the ability to quickly increase or decrease resources according to the needs. Scaling can happen horizontally (scaling out) or vertically (scaling up). Cloud computing makes it easy to scale applications and often allow you to do so automatically based on usage patterns.

### Benefits of cloud scalability:

Scalability is the key concept for anyone in the DevOps world.

### Performance:


One core benefit of scalability in the cloud is that it facilitates performance. Scalable architecture has the ability to handle the bursts of traffic and heavy workloads that will come with business growth.

- Cost-efficient:

You can allow your business to grow without making any expensive changes in the current setup. This reduces the cost implications of storage growth making scalability in the cloud very cost effective.

- Easy and Quick:

Scaling up or scaling out in the cloud is simpler; you can commission additional VMs with a few clicks and after the payment is processed, the additional resources are available without any delay.

- Capacity:

Scalability ensures that with the continuous growth of your business the storage space in cloud grows as well. Scalable cloud computing systems accommodate your data growth requirements. With scalability, you don’t have to worry about additional capacity needs.
