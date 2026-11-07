# DevelApp-ai `.github`

Organization-level configuration for the DevelApp-ai org — contents here apply org-wide.

- **`workflow-templates/`** — starter workflows offered in every repository's **Actions → New workflow** picker.
  - [`sbob-publish.yml`](workflow-templates/sbob-publish.yml) — publish a cosign keyless-signed SBoB profile to a registry repo you own, through the reusable lane in [SBOB-Forge](https://github.com/DevelApp-ai/SBOB-Forge). Prerequisites, trust model and secrets are documented in the [SBOB adoption guide](https://github.com/DevelApp-ai/SBOB-Forge/blob/main/docs/adoption.md).

The canonical copy of the template is maintained in [SBOB-Forge](https://github.com/DevelApp-ai/SBOB-Forge/tree/main/.github/workflow-templates); the SBOB-Forge `action-smoke` CI lane byte-identity-checks this repo's copy against it on every PR and on main.
