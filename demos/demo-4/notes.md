# Demo 4

Demonstrates the creation of a new pipeline job in Jenkins. Requires an existing SCM repository and a checked in `Jenkinsfile`.

## Starting Jenkins

* Start Jenkins.
* Open Jenkins in the browser of your choice.

## Creating a new job

* Click _New Item_ in the left-hand menu.
* In the following screen, enter a job name. Pick the job type _Pipeline_ or _Multibranch Pipeline_.
* Press the _OK_ button.

![Create New Job](./images/create-job.png)

## Configuring the pipeline

* In the job configuration, pick "Pipeline script from SCM" in the section _Pipeline_.
* Select "Git" from the drop-down named "SCM".
* Enter the repository URL.
* Save the job.

![Configure Pipeline](./images/configure-pipeline.png)