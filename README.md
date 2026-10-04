# MyPageAudit's GitHub home

This repository introduces MyPageAudit to visitors and holds the shared guides we use to work together. The organization's Overview page displays [profile/README.md](profile/README.md); this root README explains how to maintain it.

## What belongs where

| Location                                             | Purpose                                                                                             |
| ---------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| [profile/README.md](profile/README.md)               | Public introduction, current features, repository guide, and product direction                      |
| [profile/avatar.png](profile/avatar.png)             | Generated MyPageAudit icon used in the public README and ready to upload as the organization avatar |
| [profile/avatar.svg](profile/avatar.svg)             | Simplified vector companion for the brand icon                                                      |
| [docs/PROFILE_SETUP.md](docs/PROFILE_SETUP.md)       | Set up the public README, short description, and organization avatar                                |
| [CONTRIBUTING.md](CONTRIBUTING.md)                   | Where to propose changes and how to prepare a contribution                                          |
| [SECURITY.md](SECURITY.md)                           | How to report a sensitive security concern                                                          |
| [ISSUE_TEMPLATE](ISSUE_TEMPLATE)                     | Forms for reproducible bugs and product ideas                                                       |
| [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) | Context and verification to include in a pull request                                               |
| [.github/workflows/ci.yml](.github/workflows/ci.yml) | Basic checks for community files and the vector profile asset                                       |

## Show the profile on GitHub

The `mypageaudit/.github` repository must be **public**, and `profile/README.md` must be committed on its default branch. Other application repositories can stay private. The organization description and avatar are separate profile settings; committing this README does not update those fields automatically.

Follow the [profile setup guide](docs/PROFILE_SETUP.md) for the exact steps and suggested description. GitHub also documents [organization profile requirements](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

## Keep the introduction useful

Use plain language, link to the actual GitHub repository names, and keep current features separate from future plans. When a capability ships or a repository moves, update the public profile alongside the product documentation. Avoid publishing internal credentials or customer information here.

Application instructions live in [audit-client](https://github.com/mypageaudit/audit-client) and [audit-server](https://github.com/mypageaudit/audit-server). Product planning and release coordination live in [organization](https://github.com/mypageaudit/organization). This repository contains community content and has no runtime application image.
