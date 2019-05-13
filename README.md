# generamba-templates

This repository contains a list of [Generamba](https://github.com/rambler-digital-solutions/Generamba) templates.

The detailed information about a template structure is available in [Generamba Wiki](https://github.com/rambler-digital-solutions/Generamba/wiki/Template-Structure).

## Requirements

[Generamba](https://github.com/rambler-digital-solutions/Generamba) 1.3.0 or later.

## List of templates

* [Moon MVP module]() - generates a new module of **MVP** architecture

* [Moon MVP Coordinatable module]() - generates a new module of architecture **MVP** with routing using Coordinators.

* [Moon MVP Coordinatable Alert module]() - generates a new alert module of architecture **MVP** with routing using Coordinators.

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/mkdk/generamba-templates'

### Templates
templates:
- {name: needed_template_name}
```

## Special thanks to @ismetanin, @s4x
