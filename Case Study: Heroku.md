Research and review the various ways you could use Heroku to implement a CI solution. Describe where the various technologies Heroku has to offer fit into each of the testing environments. Document a possible approach on how to use it for your next "online game project". Submit this as a .md page on your github.io site.

Starting Reference: https://www.heroku.com/flow

## Research and Review

You can find a CI (Continous Integration) solution by following the Heroku Flow. The Heroku Flow starts with Heroku Pipelines. Heroku Pipelines organizes a group of Heroku apps sharing the same codebase and places them into their proper testing environments to ensure continuous delivery. Heroku CI works alongside Heruko Pipelines to provide continuous integration and delivery. Heroku CI runs your test scripts, using disposable apps that flow well with your staging and production testing environments. Heroku can create a temporary test app that is automatically updated with each new commit. This helps to test if potential merges should be integrated into the final product or not. Heroku ChatOps is a system used by developers to communictate with each other and keep tracking of any current or past changes made to the overall product. Developers also recieve Pull Request notifications so that they are always informed about the project's progress. Release Phase is the final step in the Heroku Flow. It lets you run tasks before moving on to the production testing environment.

## Development Environment

## QA Environment

## Staging/Pilot Environment

## Production Environment

