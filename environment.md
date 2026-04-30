# Environment

* Functional area in which we deploy and run our build process application projects
* We use environment to control how we deploy and execute projects
* A project can be deployed in more than one environment and for different project versions
* By creating shared environments, you can increase the security of deployed projects and the corresponding artifacts and resources, by limiting access and managing project members

2 types of environment:

* Shared:
  * Created by users with the ProcessAutomationAdmin role anc can be shared to users with ProcessAutimationDeveloper role
  * By creating more than one shared shared environment on sap bpa tenant, we can isolate the deployment of different project or versions
* Public:
  * Contains all of the existing projects already deployed in sap bpa
  * The settings in the environment correspnd to the settings alreayd made for these projects
  * Access to the public environment is protected at the tenant level so every user who has access to the tenant has access to the public environment



* Each environment contains distinct consigurations that define the conditions for the running projects
* These include: Project, Automation Launchers, Triggers, Agent management, Alert handlers, Variables, API kets, visibility scenario, Process and workflow
