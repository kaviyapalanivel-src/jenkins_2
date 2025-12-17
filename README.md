# Jenkins Task-2

## Task
Create a script, push it to GitHub, connect the repo to Jenkins, and trigger a build automatically on every commit.

## Tools Used
- AWS EC2
- Jenkins
- GitHub

## What I Did

1. Launched an EC2 instance and installed Jenkins.
2. Created a GitHub repository.
3. Created a simple shell script and pushed it to the repository.
4. Created a Freestyle project in Jenkins.
5. Connected Jenkins to the GitHub repository.
6. Enabled GitHub webhook for automatic build trigger.
7. Verified that Jenkins builds automatically when code is pushed.
8. Shared the build output through email.

## Script Used
```bash
#!/bin/bash
echo "Jenkins build triggered"
date
