## Scenario 
In the last version of the URL Shortener improvements were made to the program by automizing the deployment of applications when a change is committed to Git Hub. But with great power comes great responsibility. In this case, a new hire committed version 2 of the application to the main branch. Which automatically triggered a build, test, and deployment to the production server, replacing version 1 of the application running on the server.
## The Story
We’re a tech start-up company with a URL shortener tool. We have an SLA with Nike to provide them access to our URL shortener. In the SLA, we are only allowed 20 minutes of downtime a year. If anything happens to the URL shortener, we must communicate any incidents to Nike.

## Solution
In response to the unexpected deployment of version 2, the team opted for a quick rollback to version 1, a decision that helped minimize downtime and maintain our SLA commitment with Nike. Subsequent debugging of v2 allowed us to address the issues and refine our automation process. This highlights the significance of robust testing and quality control in deployments to ensure seamless service for clients like Nike.
