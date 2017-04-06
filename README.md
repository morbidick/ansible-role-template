# My ansible role template

[![Build Status](https://travis-ci.org/morbidick/ansible-role-template.svg?branch=master)](https://travis-ci.org/morbidick/ansible-role-template)

This is a template for ansible roles

## Requirements

None.

## Example playbook

```` yaml
- hosts: all
  become: yes

  roles:
  - template
````

## Role variables

None of the variables below are required.

| Variable                 | Default   | Comment |
| :---                     | :---      | :--- |
| `role_production_ready`  | `false`   | Basic demo entry |

For all options see [defaults/main.yml](defaults/main.yml)

## Development

You can use the Vagrantfile for local testing, just install vagrant and virtualbox and execute the following commands:

````bash
vagrant up
vagrant provision
````

## TODO

- [ ] *meta* update author
- [ ] *meta* update description
- [ ] *meta* update tags
- [ ] *readme* update travis batch url
- [ ] activate travis tests

## License

MIT
