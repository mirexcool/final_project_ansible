In this reposotory located all roles and playbooks for Ansible jobs.

--------------------
setup_tomcat.yml
    This playbook starts ansible role setup_tomcat wich will setup environment on each server defined in hosts.txt.
    Role can setup Apache Tomcat on both linux destributives, such as Debian or RedHat.

--------------------
deploy_to_tomcat.yml
    This playbook starts ansible role deploy_to_tomcat wich will deploy artifact from S3 bucket to all servers(defined is hosts.txt).

--------------------
Directory configs
    Here are storing some configs for tomcat service.