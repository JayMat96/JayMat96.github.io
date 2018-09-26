Which Testing Types can be used in the different sections of the Heroku Flow?

Starting Reference: https://www.heroku.com/flow

# Research and Review

CI stands for Continous Integration. It is a software engineering practice in which isolated changes are immediately tested and reported on when they are added to a larger code base.

You can find a CI (Continous Integration) solution by following the Heroku Flow. The Heroku Flow starts with Heroku Pipelines. Heroku Pipelines organizes a group of Heroku apps sharing the same codebase and places them into their proper testing environments to ensure continuous delivery. Heroku CI works alongside Heruko Pipelines to provide continuous integration and delivery. Heroku CI runs your test scripts, using disposable apps that flow well with your staging and production testing environments. Heroku can create a temporary test app that is automatically updated with each new commit. This helps to test if potential merges should be integrated into the final product or not. Heroku ChatOps is a system used by developers to communictate with each other and keep tracking of any current or past changes made to the overall product. Developers also recieve Pull Request notifications so that they are always informed about the project's progress. Release Phase is the final step in the Heroku Flow. It lets you run tasks before moving on to the production testing environment. 

Following the Heroku Flow ensures that the project is always being worked on, and that the developers working on it always know the status of the project.

# Different Testing Types and Heroku



# Heroku Use in Testing Environments

## Development Environment
  
  Heroku ChatOps and the Review App tools would work well in the Developemt environment. Heroku ChatOps lets developers communictate with each other over any changes made. Review Apps lets the developers test any changes before adding them to the master build.

## QA Environment

  Using a Review App is a good idea for the QA testing environment. Using the Review App, you can focus only on the new changes made. You can have testers check the most recent version of a project and look for any problems, before finalizing any changes.

## Staging/Pilot Environment

  You can use a combination of the Review App and Heroku ChatOps tools for the Staging/Pilot Environment. Since the Staging/Pilot environment works as a Pre-Production environment, you can use both tools to bridge the gap between the final version of the build and the earlier version. Developers can communicate with each other over what changes were made in response to QA testing.

## Production Environment

  Release Phase is a perfect fit for the production testing environment since it handles the most up-to-date version of a product. You can have testers test the most current and possibly final build of the project.
  
  # Use for Project

Looking at what Heroku has to offer, most of the techniques and tools can be done with GitHub. One exception is the Review App. It might be possible to create a Review App, but it will not be as simple or fast as by using Heroku. We can always make a seperate branch to work on the project and test, before applying it to the master branch. 

GitHub does have it's own version of Heroku ChatOps making communuication within the group easy. So long as everyone is checking what changes have been made before starting work, we should do fine. This is to ensure that no one is wasting time by working on something that another team member is already working on or contradicting another team member's work.

As long as we communicate with each other, perform our assigned tasks, and check our project's status, we will have a complete project in time.
