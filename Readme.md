# NethServer DigitalOcean Marketplace Image

Generate a base Nethserver image for the DigitalOcean Marketplace.

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
