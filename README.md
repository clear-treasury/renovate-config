# Renovate Config

Shared renovate config preset for all Clear Treasury repositories.

# How to use this config

Every repo under the
[clear-treasury GitHub org](https://github.com/clear-treasury) should have a
`renovate.json` file.

1. Create a `renovate.json` file at the repo root
2. Add the following as the file's contents:

```json
{
  "extends": ["github>clear-treasury/renovate-config"]
}
```

# What does the config do?

The shared config defines the following options:

- Extends the
  [base config](https://docs.renovatebot.com/presets-config/#configbase)
- Removes `header` and `configDescription` from
  [prBodyTemplate](https://docs.renovatebot.com/configuration-options/#prbodytemplate)
  to reduce noise

# Further reading

- Renovate
  [Shareable Config Presets](https://docs.renovatebot.com/config-presets/)
  documentation
- Renovate
  [Configuration Options](https://docs.renovatebot.com/configuration-options/)
  documentation
