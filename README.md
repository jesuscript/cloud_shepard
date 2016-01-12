# Cloud Shepard

## A IaaS management utility

Currently supports Digital Ocean

### Installation

```
npm install -g cloud-shepard
```

### Usage

```
$ ./bin/cloud_shepard --help

Cloud Shepard

A very kind cloud control automation tool

Synopsis

$ cloud-shepard create|destroy|list|inventory -c <config file> [args]

-p, --api-key string   DigitalOcean API key
-h, --help             Show usage

create

-s, --ssh-key string              Public ssh key file
-w, --write-inventory-to string   Path for saving the inventory file
-c, --config string               Configuration file (required)

inventory

-w, --write-inventory-to string   Path for saving the inventory file
-c, --config string               Configuration file (required)

```

An example config file can be found in `/example`

```
$ cloud-shepard create -c my-config.json
```
