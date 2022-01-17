# Setup Ansible Controller

Since we're using Ansible Controller (aka Ansible Tower), 
it's a good idea to automate its configuration. 

To run it, copy the file `extra_vars_example.yml` and 
change the values:
- Ansible Controller URL
- Ansible Controller credentials
- ServiceNow environment (XXXX from https://
- ServiceNow credentials (admin/xxxxxx) 

Steps are as follows:
- Create a new Credential Type for Service Now
- Create a new Service Now Credential
- Create a Project
- Create a Job Template, using the WebHook
