# Schemas

[![Release][repo-current-release-image]][repo-url]
[![License][license-image]][license-url]

Repository containing custom schemas used within the Department for Work and Pensions for onward publication to [SchemaStore.org][schema-store]

## Using Schemas

[Supported editors][supported-editors] should automatically detect and validate these schemas. If you are using [`yaml-language-server`][yaml-language-server] and want to force a specific hosting location or version you can include the following in your [yaml][yaml] document:

```yaml
%YAML 1.2
# yaml-language-server: $schema=https://raw.githubusercontent.com/dwp/schemas/blob/<branch-or-tag>/<path>/<schema-name>.json
---
my_content:
```

Replacing the placeholders `<branch-or-tag>`, `<path>` and `<schema-name>` as appropriate.

<!---

## Available Schemas

### `schema-name.json`

--->

[license-image]: https://img.shields.io/badge/license-ISC-green
[license-url]: https://opensource.org/licenses/ISC
[repo-current-release-image]: https://img.shields.io/github/v/tag/dwp/schemas?include_prereleases
[repo-url]: https://github.com/dwp/schemas
[schema-store]: https://www.schemastore.org/json/
[supported-editors]: http://json-schema.org/implementations.html#editors
[yaml]: https://wikipedia.org/wiki/YAML
[yaml-language-server]: https://github.com/redhat-developer/yaml-language-server
