Install Groovy plugin in jenkins:

image

Create a new job with Freestyle template. and configure the script in the job as shown below.

image

Or keep the script in GitHub and configure it in the jenkins job.

image

Refer the groovy file in jenkins job configuration:

image

If you want to pass the paramter from jenkins and read the parameter value in groovy script.
image

image

Known Issue:
image

Solution: Go to ManageJenkins --> In-Process script Approval --> Approve (You may need to do this again whenever you get this type of issue)
image

image
