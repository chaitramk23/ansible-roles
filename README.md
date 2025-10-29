# nginx-role

This Ansible role installs and configures the Nginx web server on Ubuntu.

## Requirements

- Ansible >= 2.13
- Supported OS: Ubuntu 20.04 / 22.04

## Role Variables

You can override these defaults in your playbook:

```yaml
nginx_port: 80
# nginx-role

This Ansible role installs and configures Nginx on target hosts.

## Requirements
None

## Role Variables
| Variable | Default | Description |
|-----------|----------|-------------|
| `nginx_port` | `80` | Port for Nginx service |

## Example Playbook
```yaml
- hosts: web
  roles:
    - nginx-role
