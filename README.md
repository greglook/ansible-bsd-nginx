Ansible BSD NGINX Role
======================

Ansible role for installing NGINX on FreeBSD as a reverse proxy.

In the simple case where you want to proxy HTTP to some backend service, you can
set the `nginx_proxy_{scheme,address,port}` variables. These default to `http`,
`localhost`, and `8080` respectively.

For more control over the nginx config, set the `nginx_config` to a dictionary
with `upstreams` and `servers` entries. See the `[defaults](defaults/main.yml)`
file for examples.
