# locales

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/locales)
[![General Workflow](https://github.com/rolehippie/locales/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/locales/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/locales/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/locales/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/locales/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/locales/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/locales)](https://github.com/rolehippie/locales/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/51429)](https://galaxy.ansible.com/rolehippie/locales)

Ansible role to configure system locales.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [locales_available](#locales_available)
  - [locales_extra](#locales_extra)
  - [locales_lang](#locales_lang)
  - [locales_packs](#locales_packs)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### locales_available

List of available locales

#### Default value

```YAML
locales_available:
  - en_US.UTF-8
```

### locales_extra

Optional dict of additional locales

#### Default value

```YAML
locales_extra: {}
```

### locales_lang

Default language to use on the system

#### Default value

```YAML
locales_lang: en_US.UTF-8
```

### locales_packs

List of language packs to install

#### Default value

```YAML
locales_packs:
  - language-pack-en
  - language-pack-en-base
```

## Discovered Tags

**_locales_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
