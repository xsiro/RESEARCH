"I am Daniel Ruiz, an student from CITM of videogames degree. This is my research about automated builds from project 2".

# AUTOMATED BUILDS

## What is an automated build?
Automated builds are a practise of automatic building a software typically on every commit. Often could why we are testing, so you can understand very quickly if any commits causing any issues in the build and unit testing process.

## Continuous integration (CI)
  The continuous integration is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.

### Benefits
- Say goodbye to long and tense integrations
- Increase visibility enabling greater communication
- Catch issues early and nip them in the bud
- Spend less time debugging and more time adding features
- Build a solid foundation
- Stop waiting to find out if your code’s going to work
- Reduce integration problems allowing you to deliver software more rapidly

## Continuous delivery (CD)
Continuous Delivery is the ability to get changes of all types, including new features, configuration changes, bug fixes and experiments into production, or into the hands of users, safely and quickly in a sustainable way.

### Benefits
- Low risk releases: make the software deployments painless 
- Faster time to market
- Higher quality
- Lower costs
- Better products
- Happier team

## Continuous deployment (CD)
Continuous deployment is a strategy for software releases where in any code commit that passes the automated testing phase is automatically released into the production environment, making changes that are visible to the software's users.

### Benefits
- Eliminate DIY for Continuous Delivery and increase the focus on the product.
- Automate the repetitive tasks and focus on actual testing.
- Make deployments frictionless without compromising security.
- Scale from a single application to an Enterprise IT portfolio.
- Connect your existing tools and technologies (such as CI providers, DevOps tools, or scripts) into a harmonious workflow.
- Integrate teams and processes with a unified pipeline.
- Create workflows across the development, testing, and production environments
- Provide a single view across all applications and environments.
- Ship both cloud-native and traditional applications in a unified pipeline.
- Improve overall productivity.

## AppVeyor

### What is AppVeyor?
AppVeyor is a program that every time a commit is done to the code, it automatically uploads the build with all the needed artifacts to the Release page of GitHub giving you feedback of how the build has been done.

## Tutorial

### Starting
- To begin with, we will need to create an account on AppVeyor using our GitHub account.
- Then, we will need to authorize it. If the GitHub repository to apply it is from an organization, it will require the authorization of the organization's owner. So it’s recommended to be done by the owner himself.
![](Docs/Images/captura1.png)
Once we have synchronized both applications, we can go on with AppVeyor creating a new project and selecting the GitHub repository which we want to have automated builds.
Now we have our project in AppVeyor, by default every time we make a commit, it will try to make a built, but it probably fails due to the app configuration is not the correct. So the next step is how to configure it.


