# Jarvis Theme for Home Assistant

Dark glass theme with cyan glowing borders, rounded cards and orange accents.

## Requirements

- [card-mod](https://github.com/thomasloven/lovelace-card-mod) (HACS), loaded via `frontend: extra_module_url`

## Installation (HACS)

1. HACS → three dots → **Custom repositories**
2. Add this repository URL, category **Theme**
3. Install **Jarvis Theme**
4. Make sure `configuration.yaml` contains:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

5. Restart Home Assistant or call `frontend.reload_themes`
6. Select **Jarvis** in your profile (or per dashboard view with `theme: Jarvis`)

## Customize

Accent colors are defined at the top of `themes/Jarvis.yaml` (`jarvis-cyan`, `jarvis-orange`).

## License

MIT
