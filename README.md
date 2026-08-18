# GiveawayX Mintlify Documentation Bundle

This bundle contains the complete **English** documentation set prepared from the supplied GiveawayBot and GiveawayX Dashboard source code. It contains 21 Mintlify MDX pages, a root `docs.json`, the original GiveawayX logo and circular bot icon, and selected dashboard screenshots.

## Deploy to the linked Mintlify repository

Copy the contents of this bundle into the root of the repository connected to Mintlify. Commit and push the changes. Mintlify uses a docs-as-code workflow: pages are stored in the repository and deployments are triggered by repository updates. [1]

```bash
# From the root of your Mintlify-connected docs repository
cp -R /path/to/GiveawayX-Mintlify-Docs/. .
git add docs.json index.mdx get-started giveaways dashboard bot reference assets README.md
git commit -m "docs: add comprehensive GiveawayX documentation"
git push
```

## Bundle structure

| Path | Purpose |
| --- | --- |
| `docs.json` | Mintlify theme, brand, navigation, search/contextual settings, and project metadata. |
| `index.mdx` | Documentation landing page. |
| `get-started/` | Initial configuration, self-hosting, and first giveaway guidance. |
| `giveaways/` | Giveaway Studio, eligibility, rewards, scheduling, templates, and live-event management. |
| `dashboard/` | Every active dashboard area, plus visibility notes for Premium and Coming Soon sections. |
| `bot/` | Categorized slash-command, utility, community, and automation reference. |
| `reference/` | Permissions, feature availability, and troubleshooting. |
| `assets/` | Original GiveawayX logo/icon plus dashboard screenshots. |

## Verification status

The bundle passed a static verification: all 21 navigation entries point to existing MDX pages, every page contains frontmatter, and all configured logo/favicon assets exist. Before publishing, use the Mintlify preview or deployment preview to make any product-specific link, policy, or support-channel updates.

[1]: https://www.mintlify.com/docs/quickstart "Mintlify Quickstart"
