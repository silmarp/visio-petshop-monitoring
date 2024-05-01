# Visio petshop monitoring
> Observability project for visio selection.

Monitor metrics from a petshop app and linux host using docker, prometheus, node_exporter and grafana for visualization and alerts.
  
![](header.png)

## Usage 

```sh
docker compose up
```

## Development setup

Nix:

```sh
nix develop
```

Linux:

Install docker, docker compose and ansible with your package manager of choice.

## Deploy using ansible

Remember to change the inventory to hosts you have access

```sh
ansible-playbook -i ansible/inventory.ini ansible/deploy.yml
```
