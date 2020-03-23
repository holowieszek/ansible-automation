# ANSIBLE-AUTOMATION
Testing automation with Ansible.  

### RUN
`ansible-playbook setup-app.yml`

#### Ping all hosts
`ansible-playbook setup-app.yml --tags ping`

#### WORKFLOW:
yum updates on all hosts  
install httpd on the webservers  
check if apache works  
upload hello.html to the webservers  
create index.html on all webservers  
install httpd & php on the loadbalancer(s)  
check if apache works
configure loadbalancer  
restart loadbalancer(s)