Vagrant Squeeze 64
==================

Uses the image from (https://s3-eu-west-1.amazonaws.com/rosstimson-vagrant-boxes/debian-squeeze-64-rvm.box)

Installs the following software:
- php
- apache2
- postgresql server
- openssl (dependency for postgresql)
- openjdk java

Provisioned with Chef-Solo.

The postgresql cookbook had to be modified a bit so that apt-get update is run before it's trying to install postgresql-client
