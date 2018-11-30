# Nethserver DigitalOcean snapshot generator

Generate a base Nethserver 7.5 image that can be used for create new droplets.

**WARNING**

The builded image in not updated, so must be manually update or enable automatic
updates before use for production.

## Requirements

* [packer.io](https://packer.io/)
* [ansible](https://www.ansible.com/)

## Usage

* Generate a new API token and set:
```
export DIGITALOCEAN_API_TOKEN=<TOKEN>
```

* Build new snapshot:
```
packer.io build packer.json 
```
