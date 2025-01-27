# DevOps Course HW2

## Synopsis

Using an ansible playbook and docker-compose an nginx webserver is deployed inside a docker sharing the webpage folder so that the server doesn't (have to) restart when changes are made to the html.

## Requirements

- ansible
- arch based system
- community.general.pacman module

## How to run

1. On an arch based system, clone the repository
2. Do some docker setup yourself :P (idk)
3. Run the playbook with ```ansible-playbook playbook.yml -i inventory --ask-become-pass```
4. (Optional) Checkout ```http://localhost:8080/```
