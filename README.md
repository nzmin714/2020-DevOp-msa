<h1>2020-DevOp-msa</h1>

Deployed website on Azure: https://2020-devops-msa.azurewebsites.net/

Build Pipeline checks linked git repo for updates. Runs a scripts to check for any installations required. Goes into directed files and 'npm run build'.
Release Pipeline uses continuous integration so that everytime a commit is made to the repo the build pipeline runs and automatically creates a release pipeline.
