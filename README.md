# ansible_role_centos_on_gcp

An Ansible role to deploy a Centos VM on Google Cloud Platform

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should
be mentioned here. For instance, if the role uses the EC2 module, it may be a
good idea to mention in this section that the boto package is required.

## Role Variables

All over-writable variables used in this role are defined in defaults/main.yml.

The variables are grouped into sections, where the variables that are intended
to be frequently changed/overridden are defined first and variables that are
less likely to be changed are defined last.

You can override the variables in any standard Ansible-way (e.g. group_vars,
host_vars, playbook variables, command-line, etc.).

The variables in this role include:

|Name|Description|Type|Default|
|---|---|---|---|
|TBD|TBD|TBD|TBD|

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in
regards to parameters that may need to be set for other roles, or variables
that are used from other roles.

|Role|Description|Version|
|---|---|---|
|TBD|TBD|TBD|

## Example Playbook

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## License

MIT

## Author Information

|Author|E-mail|
|---|---|
|Ben Watson|bwatson1979@gmail.com|

## Role Development Information

### Contributing

1. Fork it
1. Create your feature branch (`git checkout -b my-new-feature`)
1. Commit your changes (`git commit -am 'Add some feature'`)
1. Push to the branch (`git push origin my-new-feature`)
1. Create new Pull Request

### Git SCM
Please refer to the .gitignore file and update accordingly depending on your
development environment, etc.  The particular file was generated at
gitignore.io and contains settings for the following:
  - Ansible
  - Python
  - Vim
  - Eclipse
  - IntelliJ IDEA
  - Linux
  - Windows

### Versioning
Please update VERSION.md as you release new versions of your role and try to
abide by Semantic Versioning (compatibility).

Please consider using Gitflow such that individuals that want to use your role
can identify a version (e.g. master, develop, <tag>, etc.) to use.
  - https://danielkummer.github.io/git-flow-cheatsheet/
  - http://nvie.com/posts/a-successful-git-branching-model/

### Self-contained
Please try to keep this role as self-contained as possible such that it may be
simply installed (e.g. ansible-galaxy install) and applied as part of a
playbook.