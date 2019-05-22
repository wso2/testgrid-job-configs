# testgrid-job-configs

This repo holds the job configurations of each Testgrid job. Each branch correspond to a particular deployment. That means,

* _master_ - this branch is for testgrid production deployment - https://testgrid-live.private.wso2.com/
* _devenv_ - this branch is for testgrid dev deployment - https://testgrid-live-dev.private.wso2.com/

## How this works?

If you want a Testgrid job, you just need to create a job config file similar to [reference-testgrid.yaml](https://github.com/wso2/testgrid-job-configs/blob/527e09dff845718338a0ce9cfd528065f95e78b9/team-tg/reference-testgrid.yaml)
, and send a pull request. When the PR is merged, a Testgrid job will get created automatically in the corresponding tg deployment (prod/devenv). You can now head over to the TG deployment, and trigger a build of your job.

At the end of the build, you get an email with the build results with a link to dashboard for further details. 
Only the people in the _emailToList_ value of your own job configuration receive the emails; you can configure this as you wish.
