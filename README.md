# DevOps Workshop with OpenShift and OpenShift Ansible Broker

The DevOps Workshop provides full-stack and DevOps engineers an introduction to OpenShift, OpenShift Ansible Broker and containers and how OpenShift and Ansible can be used to build fully automated end-to-end deployment pipelines using advanced deployments techniques like rolling deploys and blue-green deployment.

The lab application used in this workshop is available at https://github.com/openshift-labs/devops-oab-labs

# Agenda
* DevOps Introduction
* Create DEV Environment
* Create a Deployment Pipeline
* Running the CI/CD Pipeline on Every Change
* Automate Provisioning Traditional Databases on VMs 
* Create PROD Environment
* Promote Releases to Production
* Zero-Downtime Deployment in Production

# Workshop Guides

You can deploy the workshop guides on OpenShift using the provided template:
```
$ oc new-app -f openshift/guides-template.yml --param=OPENSHIFT_MASTER=$(oc whoami --show-server) 
```
