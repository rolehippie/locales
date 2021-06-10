# locales

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/locales) [![Testing Build](https://github.com/rolehippie/locales/workflows/testing/badge.svg)](https://github.com/rolehippie/locales/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/locales/workflows/readme/badge.svg)](https://github.com/rolehippie/locales/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/locales/workflows/galaxy/badge.svg)](https://github.com/rolehippie/locales/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/locales)](https://github.com/rolehippie/locales/blob/master/LICENSE) 

Ansible role to configure system locales. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [locales_available](#locales_available)
  * [locales_lang](#locales_lang)
  * [locales_packs](#locales_packs)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### locales_available

List of available locales

#### Default value

```YAML
locales_available:
  - en_US.UTF-8
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

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
