# Home Assistant config

Sanitized, auto-generated copy of a Home Assistant OS instance's configuration,
published by a cron job on the homelab server. Commits happen only on change.

- `configuration.yaml`, `automations.yaml`, `scripts.yaml`, `scenes.yaml`,
  `blueprints/`, `themes/` - copied as-is. `!secret` values are not included.
- `dashboards/` - storage-mode dashboards exported to YAML. To restore one,
  open it, Edit, Raw configuration editor, paste.
- `helpers/` - options of the UI-created template and utility_meter helpers.
- `lovelace_resources.yaml` - frontend cards (installed via HACS) the
  dashboards depend on.

Not a full backup: registries, integration config entries, credentials and the
recorder database are deliberately left out.
