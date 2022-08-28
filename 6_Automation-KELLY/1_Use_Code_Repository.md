# Use Source Repositories for Code Source Control

### Why do this
 - USE AWS to host your reasearch job(s) source code
 - BUILD a [CI/CD pipeline](https://aws.amazon.com/getting-started/hands-on/set-up-ci-cd-pipeline/) on AWS 

### What is this
 - Code repository hosted on AWS - can be new or mirror of existing code repo
 - Supports integration with GitHub or Bitbucket

### Key considerations
 - Code Repositories can be easily integrated with other AWS services, such as S3 buckets, CloudFormation, and CodeBuild
 - Use integrated code source repositories to build a CI/CD pipeline using other AWS services, such as CloudBuild

### How to do this
 - CREATE a new or connect an existing code repository (GitHub or Bitbucket) to get started
 - DO the quickstart to create a new code repository
 - SET UP authentication - Code Repositories supports the following types of authentication: SSH, Cloud SDK or
manually generated credentials - [link](https://amazon.com/getting-started/hands-on/set-up-code-repository/)
 - SET UP a CI/CD pipeline - [link](https://aws.amazon.com/getting-started/hands-on/set-up-ci-cd-pipeline/)

### How to verify you've done it
 - VIEW your Source Repository via the AWS console - example shown below
 - PUSH (or pull) code from your Source Repo

***add screenshot***

### Other Things to Know
 - Use integrated search to intelligently search any Source Repository code - [link]()https://cloud.google.com/source-repositories/docs/searching-code
 - Source Repositories are integrated with Stackdriver activity log readers

### How to learn more
 - 📘 Read 'Gitops CI/CD with Cloud Build and Source Repositories' [link](https://cloud.google.com/kubernetes-engine/docs/tutorials/gitops-cloud-build)