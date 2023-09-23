## In the last version of the URL Shortener improvements were made to the program by automizing the deployment of applications when a change is committed to github. But with great power comes great responsibility. In this case, a new hire was able to make a change without notifying anyone, resulting in a system crash. 

## The Story
We’re a tech start-up company with a URL shortener tool. We have an SLA with Nike to provide them access to our URL shortener. In the SLA, we are only allowed 20 minutes of downtime a year. If anything happens to the URL shortener, we must communicate any incidents to Nike.

## Scenario
A new hire was tasked with updating the URL shortener. The new hire committed version 2 of the application to the main branch. Which automatically triggered a build, test, and deployment to the production server, replacing version 1 of the application running on the server.
