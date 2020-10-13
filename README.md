# locales

[![Build Status](https://cloud.drone.io/api/badges/rolehippie/locales/status.svg)](https://cloud.drone.io/rolehippie/locales)

Ansible role to configure locales

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
