# Complete_CI_CD_Project_01

In this project, I create an automated CI/CD pipeline that fetches java code from a repo on GitHub into Jenkins, builds and performs unit test using Maven, performs code analysis for bugs and code smells using SonarQube Scanner and the artifact is pushed to the Nexus software repository. 

Included in the pipeline is a post-installation step that sends notifications to dev indicating whether the pipeline executed successfully or failed using Slack Notification.

I created 3 EC2 Linux Instance Servers for:
- Jenkins (Ubuntu)
- SonarQube (Ubuntu)
- Nexus OSS (CentOS)
