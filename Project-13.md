## **Documentation for Project 13**

### Introducing Dynamic Assignment Into Our structure

### Creating another Branch named dynamic-assignments under our ansible-config-mgt repo on github

`git checkout -b dynamic-assignments`

![ansible-config-artifacts-directory-created](./Images/dynamics-assigments-branch-created.png)

### Updating site.yml with dynamic assignments

![updating-site-yml-with-dynamic-assignments](./Images/site-yml.png)

### New role created by geerlingguy installed using ansible-galaxy and folder renamed to mysql

`ansible-galaxy install geerlingguy.mysql`
`mv geerlingguy.mysql/ mysql`

![new-role-created-using-ansible-galaxy](./Images/install-mysql-role-by-gee/dynamics-assigments-branch-created.png
/site-yml.png/install-mysql-role-by-geerlingguy-renamed%20-mysql.png### Running our playbook against dev to configure msql

![Running-our-playbook-to-install-msql](./Images/mysql-succes-1.png)

![Running-our-playbook-to-install-msql](./Images/mysql-success-2.png)

![Running-our-playbook-to-install-msql](./Images/mysql-success-3.png)

### Install Nginx and Running our playbook against dev to configure nginx Load Balancer

![Running-our-playbook-and-setting-nginx-to-true](./Images/install-nginx-role-geerlingguy-renamed-nginx.png)

![Running-our-playbook-against-dev-to-install-apache](./Images/nginx-lb-success.png)