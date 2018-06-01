# myliberty
Test docker Liberty Rel 8 ---
This is a very basic docker file that deploy a sample WAR into liberty image.
This docker file is used in a CI\CD pipeline with Jenkins, to operate a test on Azure Kubernetes Services

The Git repository uses a webhook to start the Jenkins pipeline, create a docker image into an azure container registry and update a kubernetes deployment.
