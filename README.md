# ghactions-ch2-challenge
Chapter 2 challenge from GitHub Actions course
Challenge: Develop a Workflow That Creates Artifacts
In this challenge, you’ll develop a GitHub Actions workflow for a JavaScript application.

The goal is to run jobs that create and use artifacts.

In addition, you will use an Action from the GitHub Marketplace to set up an environment to use the Bun JavaScript runtime.

Github Marketplace: Setup Bun
You will also configure actions with parameters to complete their required function. 

Overview
You will complete the following steps in this challenge:

1. Create a new GitHub repository using the Node .gitignore template.
2. Open the repository in the GitHub web editor to add code and workflows.
3. Add the provided files for the Javascript application along with updating .gitignore for the project.
4. Create a multi-job workflow triggered by push and workflow_dispatch events with three jobs that run in the order listed:

One job that tests the application code, saving the test report as an artifact
One job that creates executables from the application code, saving all executables  as artifacts
One job that tests the Linux executable, saving the test report as an artifact
5. Push changes to the repository to trigger the workflow.
6. Review the Actions tab to confirm the workflow executed successfully and that all artifacts were created

This challenge should take about 15 to 20 minutes to complete.
