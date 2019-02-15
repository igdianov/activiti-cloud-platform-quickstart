# activiti-cloud-platform-quickstart

Activiti Cloud Platform Quickstart for Jenkins-X CI/CD pipelines

### Follow the steps to  Activiti Cloud GitOps environment for Jenkins-X CI/CD pipelines

We will need to use Jx Quickstart commands to create our own Activiti Cloud Platform Chart from published quickstart template in https://github/activiti organization repository

Run this command to add Activiti Quickstart location for your team:

```
jx create quickstartlocation --url https://github.com --owner activiti --kind github
```

To get the list of registered quickstart locations run command:

```
jx get quickstartlocations
```

Then, run simply run the following command to create your first runtime bundle or connector project:

```
jx create quickstart --owner activiti --filter activiti-cloud-platform-quickstart
```
