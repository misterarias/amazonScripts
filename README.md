# Amazon scripts

Collection of useful and/or funny scripts to manage AWS instances and local environments

## Requirements

* [AWS cli tools][https://aws.amazon.com/cli/]
* [jq][https://stedolan.github.io/jq/]

## Scripts

* update-public-ips

Assuming you have entries on your `/etc/hosts` for some instances, update that entries with the new public IP.
Useful if you shut them down every now and then, since the private IP stays the same (on VPCs) but the public IP changes everytime.
