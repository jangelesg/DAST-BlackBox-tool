# DAST-BlackBox-tool

DAST tool

What I'm looking at, is implementing a DAST tool (Dynamic Application Security Scan) using ZAP Proxy Attack Services in conjunction with Web Application Attack and Audit Framework into a full CI/CD pipeline, the idea is to improve our CI/CD process generating a full comprehensive Report for DevOps team

it's python-tool that consumes several REST services from the tools mentioned before, is could be be installed within DevOps Server (Bamboo, jenkins etc) and is going to Scan the WebAPP once the source code is deployed within a pre-prod env, this task will start automatically in order to find a vulnerabilties and afterwards creating a report.
