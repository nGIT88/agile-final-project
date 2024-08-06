---
name: Automation for Deploying Changes
about: template's purpose Automation for Deploying Changes
title: ''
labels: ''
assignees: ''

---

**As a** DevOps Engineer  
**I need** automation to deploy new changes to the cloud  
**So that** updates can be rolled out quickly and consistently.  

### Details and Assumptions
* The automation process should include testing and rollback capabilities.  
* Continuous integration/continuous deployment (CI/CD) practices should be followed.

### Acceptance Criteria  
```gherkin
Given a new change is committed to the code repository,
When the automated deployment pipeline runs,
Then the changes should be deployed to the cloud environment without errors.
