# Githubactions-basics 


### what is Github Actions ####
Github Actions is a continuous integration and continuos delivery(CI/CD) platform built directly into Github 

It allows you to automate various tasks with in your software development workflow 

### github actions components ####
. **Workflows** : A workflow is a configurable automated process that will run one or more jobs 
              Workflow are defined in the .github/workflows directory in repository 
              workflows are defined by a YAML file 
**. Jobs:** A job is set of steps in a workflow that is excuted on the same runner, Each step is either a shell script that will be excuted or an action that will be run 
        Steps are excuted in order and ae dependent on each other 
. **Events:** An Event is specific activity in a repo that trigger a workflow run. Based on Event workflow trigger inside workflow job is avaialble 
. **Actions:** An Action is a custom application for the github Actions platform that performs a complex but frequently repeated task.
              Use an action to help reduce the amount of repetitive code that you write in your workflow files 
**. Runners:** A runner is server that runs your workflow when they triggered. Each run runnercan run a single job at a time 
               Github provides githosted runners also we can created self hosted runner to run our workflow 
