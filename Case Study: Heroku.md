Document a possible approach on how to use it for your next "online game project". Submit this as a .md page on your github.io site.

Starting Reference: https://www.heroku.com/flow

# Research and Review

CI stands for Continous Integration. It is a software engineering practice in which isolated changes are immediately tested and reported on when they are added to a larger code base.

You can find a CI (Continous Integration) solution by following the Heroku Flow. The Heroku Flow starts with Heroku Pipelines. Heroku Pipelines organizes a group of Heroku apps sharing the same codebase and places them into their proper testing environments to ensure continuous delivery. Heroku CI works alongside Heruko Pipelines to provide continuous integration and delivery. Heroku CI runs your test scripts, using disposable apps that flow well with your staging and production testing environments. Heroku can create a temporary test app that is automatically updated with each new commit. This helps to test if potential merges should be integrated into the final product or not. Heroku ChatOps is a system used by developers to communictate with each other and keep tracking of any current or past changes made to the overall product. Developers also recieve Pull Request notifications so that they are always informed about the project's progress. Release Phase is the final step in the Heroku Flow. It lets you run tasks before moving on to the production testing environment. Following the Heroku Flow ensures that the project is always being worked on, and that the developers working on it always know the status of the project.

# Heroku Use in Testing Environments

## Development Environment
  
  Heroku ChatOps and the Review App tools would work well in the Developemt environment. Heroku ChatOps lets developers communictate with each other over any changes made. Review Apps lets the developers test any changes before adding them to the master build.

## QA Environment

  A Review App is a good tool for the QA testing environment. You can have testers check the most recent version of a project and look for any problems, before finalizing any changes. Using the Review App, you can focus only on the new changes made.

## Staging/Pilot Environment

  You can use a combination of the Review App and Heroku ChatOps tools for the Staging/Pilot Environment. Since Staging/Pilot environment works as a Pre-Production environment, you can use both tools to bridge the gap between the final version of the build and the earlier version. Developers can communicate with each other over what changes are made in response to the QA testing environment.

## Production Environment

  Release Phase is a perfect fit for the production testing environment since it handles the most up-to-date version of a product. You can have testers test the most current and possibly final build of the project.
