# CLOUD AUTOMATION ANSIBLE and TERRAFORM 

Requirements

  Ansible
  -------

  Ubuntu 

    $ sudo apt update
    $ sudo apt install software-properties-common
    $ sudo apt-add-repository --yes --update ppa:ansible/ansible
    $ sudo apt install ansible


    Reference: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu
    
  
  Terraform
  ---------

  Ubuntu

    $ wget https://releases.hashicorp.com/terraform/0.13.0/ terraform_0.13.0_linux_amd64.zip
    $ unzip terraform_0.13.0_linux_amd64.zip
    $ sudo mv terraform /usr/local/bin
    
    
    
    Reference: https://www.terraform.io/downloads.html
    
    

    AWS INFRASTRUCTURE CREDENTIALS

    $ export AWS_SECRET_ACCESS_KEY=AKI7I5QMRF6EQRETITP
    $ export AWS_SECRET_KEY=sdfwvg3MrPNsmWRmn7jwdpwq
    $ export AWS_REGION=us-east-1
