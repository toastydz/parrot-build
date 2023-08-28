Pulled and slightly modified from [ippsec](https://github.com/IppSec/parrot-build).</br>
** Make sure to pip install ansible, apt has an older copy **


# Install
* Start with [Parrot HTB Edition](https://www.parrotsec.org/download/)
* Install Ansible:</br>
  `pip3 install ansible`
* Clone and enter the repo:</br>
  `git clone  https://github.com/toastydz/parrot-build.git && cd parrot-build`
* Install requirements:</br>
  ` ansible-galaxy install -r requirements.yml`
* Make sure we have a sudo token:</br>
 ` sudo whoami`
* Run the scripts:</br>
  ` ansible-playbook main.yml`

