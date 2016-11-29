# openresty-playbook

This playbook assumes that ansible has ssh access to the remote machine via root user.

  - ansible version used for writing this module is ansible 2.2.0.0
  - This single playbook can istall openresty on Debian as well as Redhat family OS'es
  - OpenResty is compiled with pcre-jit, pcre, luajit, and http_ssl_module modules

### Command for deploying the playbook 
```sh
$ ansible-playbook -i hosts site.yml
```

For verbose output

```sh
$ ansible-playbook -i hosts site.yml -vvv
```
