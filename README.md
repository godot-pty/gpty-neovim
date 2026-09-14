# gpty-neovim

The Neovim layout for [gpty](https://github.com/godot-pty/gpty) — a gpty plugin shipping one profile: a full-grid terminal running `nvim`.

## Install

    gpty plugin install godot-pty/gpty-neovim

Installation clones this repo, validates `gpty-plugin.toml` with the shipped validator, and asks a human to review it in the gpty GUI before anything installs — a plugin's content runs as you, so acceptance is explicit and pinned to the revision you reviewed. A newer revision asks again.

## Layout

- **Neovim** — Open Neovim in a single terminal.

The profile appears in the GUI's sidebar profiles once installed-plugin profiles surface (gpty v0.5.5 profiles migration). Requires `nvim` on your `PATH`.

## License

[Apache-2.0](LICENSE) — layout data, same terms as gpty's shipped defaults.
