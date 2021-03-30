> [!NOTE]
> This project is currently in an alpha state and should be considered unstable. Breaking changes will occur. This website is a work in progress, and any API or product descriptions are subject to change.
# Deploying a project
Follow these instructions once your ADF project has been built.
First run only:
* Run Powershell as an administrator.
* Run the following command: Install-Module -Name Az in order to install the required modules. This doesn't need to be done if you already have the required modules.

Subsequent runs:
* Run the deployment script that was created in the bin folder of the Daf project.

The deployment script *should* delete all data sets, pipelines and linked services in your ADF project before re-creating them.
Currently, however, it simply deletes the data sets, pipelines and linked services matching the names of the ones currently being deployed. This can lead to orphanad ADF objects after renames, that the user should clean up manually in their ADF project.