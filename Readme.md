Pulled and slightly modified from [ippsec](https://github.com/IppSec/parrot-build).
** Make sure to pip install ansible, apt has an older copy **


# Install
* Start with [Parrot HTB Edition](https://www.parrotsec.org/download/)
* Install Ansible:
  `pip3 install ansible`
* Clone and enter the repo:
  `git clone  && cd parrot-build`
* Install requirements:
  ` ansible-galaxy install -r requirements.yml`
* Make sure we have a sudo token:
 ` sudo whoami`
* Run the scripts:
  ` ansible-playbook main.yml`

