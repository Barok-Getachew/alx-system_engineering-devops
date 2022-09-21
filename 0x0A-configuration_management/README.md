# 0x0A Configuration management

## Description
This project is an introduction to Configuration Management, as part of the third sprint curriculum of ALX SE.
This project contains very basic Puppet.

## Resources
- [Intro to Configuration Management](https://www.digitalocean.com/community/tutorials/an-introduction-to-configuration-management)
- [Puppet resource type: file (check “Resource types” for all manifest types in the left menu)](https://puppet.com/docs/puppet/5.5/types/file.html)
- [Puppet’s Declarative Language: Modeling Instead of Scripting](https://puppet.com/blog/puppets-declarative-language-modeling-instead-of-scripting/)
- [Puppet lint](http://puppet-lint.com/)
- [Puppet emacs mode](https://github.com/voxpupuli/puppet-mode)

## Install puppet
```
$ apt-get install -y ruby=1:2.7+1 --allow-downgrades
$ apt-get install -y ruby-augeas
$ apt-get install -y ruby-shadow
$ apt-get install -y puppet
```
You do not need to attempt to upgrade versions. This project is simply a set of tasks to familiarize you with the basic level syntax which is virtually identical in newer versions of Puppet.

## Install puppet-lint
```
gem install puppet-lint
```

## Table of contents
Files | Description
----- | -----------
[0-create_a_file.pp](./0-create_a_file.pp) | Puppet manifest that creates a file in the /tmp directory
[1-install_a_package.pp](./1-install_a_package.pp) | Puppet manifest that installs puppet-lint
[2-execute_a_command.pp](./2-execute_a_command.pp) | Puppet manifest that kills a process named killmenow
[killmenow](./killmenow) | Test bash script to kill with manifest 2-execute_a_command.pp
