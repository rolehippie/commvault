# commvault

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/commvault) [![General Workflow](https://github.com/rolehippie/commvault/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/commvault/actions/workflows/general.yml) [![Readme Workflow](https://github.com/rolehippie/commvault/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/commvault/actions/workflows/readme.yml) [![Galaxy Workflow](https://github.com/rolehippie/commvault/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/commvault/actions/workflows/galaxy.yml) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/commvault)](https://github.com/rolehippie/commvault/blob/master/LICENSE) [![Ansible Role](https://img.shields.io/ansible/role/55287)](https://galaxy.ansible.com/rolehippie/commvault)

Ansible role to install and configure an MongoDB cluster commvault.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [commvault_auth_code](#commvault_auth_code)
  - [commvault_auth_domain](#commvault_auth_domain)
  - [commvault_auth_password](#commvault_auth_password)
  - [commvault_auth_username](#commvault_auth_username)
  - [commvault_client_host](#commvault_client_host)
  - [commvault_client_name](#commvault_client_name)
  - [commvault_enable_install](#commvault_enable_install)
  - [commvault_installer_url](#commvault_installer_url)
  - [commvault_proxy_client](#commvault_proxy_client)
  - [commvault_proxy_host](#commvault_proxy_host)
  - [commvault_server_client](#commvault_server_client)
  - [commvault_server_host](#commvault_server_host)
  - [commvault_tunnel_port](#commvault_tunnel_port)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### commvault_auth_code

Code for client authentication

#### Default value

```YAML
commvault_auth_code:
```

### commvault_auth_domain

Domain for client authentication

#### Default value

```YAML
commvault_auth_domain:
```

### commvault_auth_password

Password for client authentication

#### Default value

```YAML
commvault_auth_password:
```

### commvault_auth_username

Username for client authentication

#### Default value

```YAML
commvault_auth_username:
```

### commvault_client_host

Hostname of the client

#### Default value

```YAML
commvault_client_host:
```

### commvault_client_name

Name of the client

#### Default value

```YAML
commvault_client_name:
```

### commvault_enable_install

Optionally disable commvault install

#### Default value

```YAML
commvault_enable_install: true
```

### commvault_installer_url

URL to donwload the installer from

#### Default value

```YAML
commvault_installer_url:
```

### commvault_proxy_client

Proxy client

#### Default value

```YAML
commvault_proxy_client:
```

### commvault_proxy_host

Proxy host

#### Default value

```YAML
commvault_proxy_host:
```

### commvault_server_client

Name of the server

#### Default value

```YAML
commvault_server_client:
```

### commvault_server_host

Hostname of the server

#### Default value

```YAML
commvault_server_host:
```

### commvault_tunnel_port

Tunnel port

#### Default value

```YAML
commvault_tunnel_port:
```

## Discovered Tags

**_commvault_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
