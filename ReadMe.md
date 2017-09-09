# Odoo

Odoo is an incredible offering for an open source ERP. Formerly known as OpenERP, this system's capabilities are impressive to say the least.

## Installation

1. Install [Docker](https://www.docker.com/community-edition#/download)
1. Clone/download this repository
1. In a terminal, execute `docker-compose up`
1. In a browser navigate to [localhost:8069](http://localhost:8069)
1. Enter 'odoo' as the database, then fill in the other forms
1. Select the 'install' button
1. Enjoy your own local Odoo instance! Install modules, configure stuff, have fun!

## Why

Making the decision to start exploring an ERP is a major undertaking for any enterprise. Compounding this is the reality that ERP systems are complex in any state. Evaluating them can require dedicated IT resources and "free trials" are often not enough to get a full understanding. This repository provides a simple way to use docker to spawn a usable Odoo instance locally, in the cloud or in your own data center as a trial environment.

## Disclaimer

This represents a trial environment only, **do NOT** use this in production. It includes hard coded very simple passwords on the database, does not implement transport layer cryptography, nor does it provide a persistance layer configuration.

If you are interested in a longer term trial, persistence, security or more than exploration please engage with an IT professional. If you don't have one, reach out!
