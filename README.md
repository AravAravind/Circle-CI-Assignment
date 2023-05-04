
CircleCI Configuration
This is a sample CircleCI configuration file for building and testing a Node.js application.

Jobs
Build
The build job builds the application by installing dependencies and running the npm run build command.

Test
The test job runs the application's tests by installing dependencies and running the npm run test command.

Workflows
Build and Test
The build-and-test workflow runs the build job first and then the test job. The test job is dependent on the successful completion of the build job.

Orbs
The node orb version 3.0.0 is used in this configuration for defining Docker images for running jobs.