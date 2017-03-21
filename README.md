jenkins-ubuntu
================

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-jenkins-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-jenkins-ubuntu)

Install Jenkins on Ubuntu.

https://galaxy.ansible.com/suzuki-shunsuke/jenkins-ubuntu/

Requirements
------------

Nothing.

Role Variables
--------------

* jenkins_jre: JRE apt package name. The default is "openjdk-8-jre"
* jenkins_jdk: JDK apt package name. The default is "openjdk-8-jdk"

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.jenkins-ubuntu
```

License
-------

MIT
