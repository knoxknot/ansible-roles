This repository contains ansible scripts that defines several roles specifying the installation and configuration of a unique application on ubuntu distro e.g docker, nginx etc.

**Usage**:
Install ansible in your control machine. Download the repository. Replace the host IP to your managed machines IPs and simply comment out any application item you do not wish to install on the managed machine and run the playbook.

**Note**: These roles are uniquely targeted at the debian distro currently.

**Commands**
- Git Versioning  
  <hr>

  - <code>git add folder/file && git commit -m "action message"</code>
  - <code>git push</code> # fill in the prompt details
- Ansible Dry Run  
  <hr>

  - <code>ansible-playbook roles.yml --check -vvvv -K</code> # fill in the prompt details
