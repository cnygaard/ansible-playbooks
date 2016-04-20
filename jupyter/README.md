# Install jupyter Python development environment
Installs a Jupyter python development environment on Ubuntu 15.10. 

### Add universe repository to sources.list
Please add universe on the end of the /etc/apt/sources.list file.

    # cat /etc/apt/sources.list
    deb http://se.archive.ubuntu.com/ubuntu/ wily main restricted universe
    deb http://security.ubuntu.com/ubuntu/ wily-security main restricted universe
    deb http://se.archive.ubuntu.com/ubuntu/ wily-updates main restricted universe

### Requires

 * Ansible, please run apt-get install ansible
 * Ubuntu, tested on Ubuntu 15.10

### How to run the ansible playbook
    ansible-playbook -c local -i hosts site.yml  

