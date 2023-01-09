# HomeServer

Repository to setup and manage my home server.
Use at your own risk. I am heavily testing different approaches and things will break.


### Create ansible-vault

```ssh
    ansible-vault create secrets.yml
```

### Edit the values

```sh
    ansible-vault edit secrets.yml
```


## Sources

### Home assistant

The playbook was inspired [this repo](https://github.com/nununo/ansible-role-proxmox-haos-install) and adapted to my needs

