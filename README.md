# HMIP

[![Deploy](https://github.com/WCRP-CMIP/MIP-template/actions/workflows/deploy.yml/badge.svg)](https://github.com/WCRP-CMIP/MIP-template/actions/workflows/deploy.yml)

Hydrogen Model Intercomparison Project (HMIP) is a Community Model Intercomparison Project dedicated to exploring and constraining the impact of hydrogen driven emissions on chemistry, climate and astmospehric parameters.

(https://alphabetagammachi.github.io/HMIP/)



## Configuration

Edit the top of `mkdocs.yml`:

```yaml
/
site_name: HMIP
site_description: Hydrogen Model Intercomparison Project (HMIP) is a Community Model Intercomparison Project dedicated to exploring and constraining the impact of hydrogen driven emissions on chemistry, climate and astmospehric parameters.
site_author: AlphaBetaGammaChi
site_url: https://AlphaBetaGammaChi.github.io/HMIP
repo_url: https://AlphaBetaGammaChi/HMIP
repo_name: AlphaBetaGammaChi/HMIP
```

## Adding Content

Navigation is auto-generated from the folder structure:

```
docs/
├── index.md           → Home
├── about/             → About section
├── experiments/       → Experiments section
└── resources/         → Resources section
```

Just add folders and `.md` files. No configuration needed.

## Documentation

See the [For Developers](docs/developers/getting-started.md) section for full instructions.

---

Built by [Daniel Ellis](https://github.com/wolfiex) for [WCRP-CMIP](https://wcrp-cmip.org) using the [shadcn](https://github.com/asiffer/mkdocs-shadcn) theme.
