# elk [one click setup ELK cluster]

This project automates the setup of an Elasticsearch cluster based on user inputs, leveraging Jenkins for orchestration, Terraform for provisioning, and shell scripts for OS detection and Elasticsearch installation.

## Prerequisites

- Jenkins
- Terraform
- Git
- SSH access to the target servers
- Deployment Automation tool Like Teraform or Ansible etc.

Need to consider user input to buld automation script as:

1. install which component (Elastic/Kibana etc.)
2. How many nodes?
3. Nodes IP
4. How many master nodes
5. How Many data nodes
6. Which Version?
7. Secure or Non-Secure
8. If Secure then custom certificate path or with Self Signed Certificate

Now according to above input we need to create automation scripts as it will create a desired Elastic CLuster.


######Avaiable Automation Deployment Tools

Jenkins, CircleCI, Octopus Deploy, Travis CI, Bamboo, GitLab, TeamCity, Terraform, Ansible, Chef, Puppet,
DeployBot, Codeship Inc., Capistrano, Codefresh, Spinnaker, Urbancode, JuJu, PDQ Deploy, ElectricFlow


Now need to select best one tool for this deployment and automate it with jenkins and that selected tool.
