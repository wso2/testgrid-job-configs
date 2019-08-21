## Purpose
> Describe the problems, issues, or needs driving this feature/fix and include links to related issues in the following format: Resolves issue1, issue2, etc.

## Task performed
- [ ] Added a new job
- [ ] Removed a job -> inform tg folks to clean the dashboard
- [ ] Added new infrastructure value
- [ ] Commented out an infrastructure value
- [ ] Added new infrastructure provisioner
- [ ] Added new test config
- [ ] Minor input parameter changes
- [ ] Other -> add a comment
<!-- 
- [x] Example ticked box -->

NOTE:
For your job, you can either point to an external testgrid yaml configuration or keep the actual testgrid yaml here within this repo. Usually, people like to keep the testgrid yaml config within their own team repos because its easier to do changes.

You can point to an external testgrid yaml by having the job configration as follows:

$> cat [testgrid-job-configs/Ballerina/bbg-kafka.yaml](https://github.com/wso2/testgrid-job-configs/blob/ce9184d7e1c3719d74ad56325239f54bff21e18b/Ballerina/bbg-kafka.yaml)
```
testgridYamlURL: https://raw.githubusercontent.com/ballerina-platform/ballerina-scenario-tests/scenario-tests/.testgrid-bbg-kafka.yaml

```
More details can be found in user guide - https://docs.google.com/document/d/1fYCUg97VsfoftEo1HfPWjdS6whp4r0noGRzfaxsxmek/edit#

