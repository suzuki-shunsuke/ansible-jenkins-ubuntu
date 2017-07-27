# jenkins-ubuntu

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-jenkins-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-jenkins-ubuntu)

ansible role to install Jenkins on Ubuntu.

https://galaxy.ansible.com/suzuki-shunsuke/jenkins-ubuntu/

## Requirements

Nothing.

## Role Variables

name | required | default | description
--- | --- | --- | ---
jenkins_jre | no | openjdk-8-jre | JRE apt package name
jenkins_jdk | no | openjdk-8-jdk | JDK apt package name

## Dependencies

Nothing.

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.jenkins-ubuntu
    become: yes
```

## License

[MIT](LICENSE)
