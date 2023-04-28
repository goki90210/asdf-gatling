# asdf-gatling [![GitHub Actions Status:Main](https://github.com/goki90210/asdf-gatling/workflows/Main%20workflow/badge.svg)](https://github.com/goki90210/asdf-gatling/actions?query=workflow%3A%22Main+workflow%22)

[Gatling](https://gatling.io/) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

Based on [tsuyoshicho/asdf-vim](https://github.com/tsuyoshicho/asdf-vim) and [elementalvoid/asdf-saml2aws](https://github.com/elementalvoid/asdf-saml2aws).

## Usage
### Install
The plugin can be install using the following command.

```
asdf plugin-add gatling
# or asdf plugin-add gatling https://github.com/goki90210/asdf-gatling.git
asdf install gatling <version>
```

### .tool-versions file
You can specify the version to install with a line like so in your .tool-versions file: gatling

### Using the CLI
You can then set the local/global version to your new version with asdf local gatling <version> or asdf global gatling <version>.

## Use
Check asdf readme for instructions on how to install & manage versions of [Gatling](https://github.com/gatling/gatling).
