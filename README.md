# resolv

[![Build Status](https://travis-ci.org/krzysztof-magosa/ansible-role-resolv.svg?branch=master)](https://travis-ci.org/krzysztof-magosa/ansible-role-resolv)

## Description
Ansible role configuring resolv.conf

## Requirements
* Ansible 2.5 or better

## Supported systems
* CentOS (tested on 7)
* Debian (tested on Buster, Stretch)
* Ubuntu (tested on Bionic)

## Docker
Please note that Docker doesn't allow containers to modify `resolv.conf`.
If you use this role against Docker container role will template `resolv.conf.docker` instead which allows testing in Docker CI/CD pipeline.

## Variables
See [defaults](defaults/main.yml).

## License
Licensed under [MIT](LICENSE.txt).
