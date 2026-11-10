# Halcyon Media Archive

Catalog site for the Halcyon archive desk. Built with Jekyll and served through
GitHub Pages as a **project site**: the published site lives under this
repository's own path on the account's Pages host, not at the account root.

## Layout

- `_catalog/` — one Markdown record per catalog entry
- `_data/gallery.yml` — manifest of publicly listed records
- `research/` — research lead sheets
- `_layouts/`, `assets/` — site theme
- `_config.yml` — site settings

## Publishing checklist

1. Attach media to the record and set its status.
2. Add the record to the gallery manifest.
3. Keep `_config.yml` in sync with the repository's final name so that
   `relative_url` links resolve correctly on the project site.
