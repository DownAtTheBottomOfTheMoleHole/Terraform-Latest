# Terraform-latest Chocolatey Package

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- Github Release BADGES -->

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/RolfMoleman/Terraform-Latest?style=for-the-badge&label=Latest%20SemVer)](https://github.com/RolfMoleman/Terraform-Latest/tags)

<!-- Github Workflow BADGES -->

[![GitHub Workflow Status (Automatically update terraform.nuspec)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/autoupdate_terraform.yml?style=for-the-badge&label=Automatically%20update%20terraform.nuspec)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/autoupdate_terraform.yml)

[![GitHub Workflow Status (build)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/build.yml?style=for-the-badge&label=Build)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/build.yml)

[![GitHub Workflow Status (Nightly Maintenance)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/scheduled_maintenance.yml?style=for-the-badge&label=Nightly%20Scheduled%20Maintenance)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/scheduled_maintenance.yml)

[![GitHub Workflow Status (Publish chocolatey package)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/publish.yml?style=for-the-badge&label=Publish%20Chocolatey%20PAckage)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/publish.yml)

[![GitHub Workflow Status (Standard Pull Request)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/pullrequest.yml?style=for-the-badge&label=Standard%20Pull%20Request)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/publish.yml)

[![GitHub Workflow Status (Sync issue to Azure DevOps work item)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/Board_Updater.yml?style=for-the-badge&label=Sync%20issue%20to%20Azure%20DevOps%20work%20item)](https://github.com/RolfMoleman/Terraform-Latest/actions/workflows/Board_Updater.yml)

<!-- Made With Badges -->

[![made%20with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg?style=for-the-badge)](https://www.gnu.org/software/bash/)
[![made%20with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg?style=for-the-badge)](http://commonmark.org)
[![made%20with-MegaLinter](https://img.shields.io/badge/Made%20with-MegaLinter-1f425f.svg?style=for-the-badge)](https://megalinter.io/latest/)
[![made%20with-PowerShell](https://img.shields.io/badge/Made%20with-PowerShell-1f425f.svg?style=for-the-badge)](https://github.com/PowerShell/PowerShell)
[![made%20with-pre-commit](https://img.shields.io/badge/Made%20with-pre--commit-1f425f.svg?style=for-the-badge)](https://github.com/pre-commit/pre-commit)

<!-- Precommit Badges -->
<!--
*** replace with badges relevant to your repo
-->

these are the pre-commit hooks used for this repo:

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-added-large-files)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-case-conflict)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-merge-conflict)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-json)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-yaml)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=detect-private-key)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=end-of-file-fixer)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=trailing-whitespace)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/streetsidesoftware/cspell.svg?style=for-the-badge&label=CSpell)](https://github.com/streetsidesoftware/cspell/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/pre-commit/mirrors-prettier.svg?style=for-the-badge&label=Prettier)](https://github.com/pre-commit/mirrors-prettier/tags)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/antonbabenko/pre-commit-terraform.svg?style=for-the-badge&label=terraform_fmt)](https://github.com/antonbabenko/pre-commit-terraform/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/antonbabenko/pre-commit-terraform.svg?style=for-the-badge&label=tfupdate)](https://github.com/antonbabenko/pre-commit-terraform/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/terraform-docs/terraform-docs.svg?style=for-the-badge&label=terraform-docs-go)](https://github.com/terraform-docs/terraform-docs/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/oxsecurity/megalinter.svg?style=for-the-badge&label=megalinter-incremental)](https://github.com/oxsecurity/megalinter/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/mattlqx/pre-commit-sign.svg?style=for-the-badge&label=pre-commit-sign)](https://github.com/mattlqx/pre-commit-sign/releases)

<!-- included tool versions -->

<!-- Azure Devops Navigation -->
<!-- markdown-table-prettify-ignore-start -->

|                                                                                                                                |                                                                                                                             |                                                                                                                      |                                                                                                                      |                                                                                                                                   |                                                                                                             |                                                                                                                             |                                                                                                                     |                                                                                                                                    |
| :----------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                |                                                                                                                             |                                                                                                                      |                                                                                                                      |                        [![terraform-latest][logo-image]](https://github.com/RolfMoleman/Terraform-Latest)                         |                                                                                                             |                                                                                                                             |                                                                                                                     |                                                                                                                                    |
|                                                                                                                                |                                                                                                                             |                                                                                                                      |                                                                                                                      |                         [**README**](https://github.com/RolfMoleman/Terraform-Latest/blob/main/README.md)                         |                                                                                                             |                                                                                                                             |                                                                                                                     |                                                                                                                                    |
|                                                                                                                                |                                                                                                                             |                                                                                                                      |                                                                                                                      |            |                                                                                                             |                                                                                                                             |                                                                                                                     |                                                                                                                                    |
| [Checkov Baseline](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/.checkov.baseline) | [Cspell config file](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/.cspell.json) | [Gitversion config](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/GitVersion.yml) | [JSCPD config](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/.jspcd.json) | [KICS config file](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/kics.config) | [License file](https://github.com/RolfMoleman/Terraform-Latest/blob/main/LICENSE) | [Megalinter config file](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/.mega-linter.yml) |  | [tflint config file](https://github.com/RolfMoleman/Terraform-Latest/blob/main/.config/build/terraform/.tflint.hcl) |

<!-- markdown-table-prettify-ignore-end -->
<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Terraform-latest Chocolatey Package](#terraform-latest-chocolatey-package)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
    - [Built With](#built-with)
    - [Terraform](#terraform)
      - [Requirements](#requirements)
      - [Resources](#resources)
      - [Inputs](#inputs)
      - [Outputs](#outputs)
      - [Modules](#modules)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
    - [Contributing Prerequisites](#contributing-prerequisites)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgments](#acknowledgments)

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://community.chocolatey.org/packages/terraform-latest)

This repository contains the code and workflows to automatically build and publish the terraform-latest chocolatey package.
this project uses a combination of dependabot and renovate to pickup the latest version fo terraform as soon as possible, to update the required_version in versions.tf and automatically produce the updated nuspec file.
Once this has happened, the branch will automatically merge with main causing the build and publish pipeline to trigger which will cpush the latest version of terraform to chocolatey :chocolate_bar:

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

### Built With

- [cspell](https://github.com/streetsidesoftware/cspell-cli)
- [GitVersion](https://github.com/GitTools/GitVersion)
- [Infracost](https://github.com/infracost/infracos)
- [Markdown](https://www.markdownguide.org/)
- [Mermaid](https://mermaid.live/)
- [Powershell](https://github.com/PowerShell/PowerShell)
- [Pre-Commit](https://pre-commit.com/)
- [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform)
- [prettier](https://github.com/prettier/prettier)
- [Terraform](https://www.terraform.io/)
- [Terraform-docs](https://github.com/terraform-docs/terraform-docs)

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- Terraform -->
### Terraform

<!-- markdown-table-prettify-ignore-start -->
<!-- markdownlint-disable -->
<!-- prettier-ignore-start -->
<!-- start_of_terraform_docs -->
The below documentation was generated via Terraform docs using pre-commit

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

#### Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | 1.7.4 |

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

#### Resources

No resources.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

#### Inputs

No inputs.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

#### Outputs

No outputs.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

#### Modules

No modules.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---
<!-- end_of_terraform_docs -->
<!-- prettier-ignore-end -->
<!-- markdownlint-enable -->
<!-- markdown-table-prettify-ignore-end -->

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

### Prerequisites

This is a list of things that would be beneficial to work on this repo.

- Install Chocolatey

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```

### Installation

1. Install the package

   ```console
   choco install terraform-latest
   ```

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- USAGE EXAMPLES -->

## Usage

to use this project install terraform-latest using Chocolatey like so:

```console
   choco install terraform-latest
```

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- ROADMAP -->

## Roadmap

- [ ] Intial release :tada:
- [ ] Fully automated terraform-latest chocolatey package lifecycle :cool:
- [ ] more professional branding :new_moon: :godmode:

See the [open issues](https://github.com/RolfMoleman/Terraform-Latest/issues?q=is%3Aopen)
for a full list of proposed features (and known issues).

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- CONTRIBUTING -->

## Contributing

Contributions are  **greatly appreciated**.

If you have a suggestion that would make this better,
please fork the Repo and create a pull request.
You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
**Note**: we ask you to please name branches sennsibly adhering to this naming convention:

1. **main** - we tend to use main now [why?](https://www.theserverside.com/feature/Why-GitHub-renamed-its-master-branch-to-main)
2. :bulb: **feature** branches created with either a `feature-` prefix or under a folder called feature.
4. :bug: **bug** branches created with either a `bug-` prefix or under a folder called bug.
5. :fast_forward: **hotfix** branches created with either a `hotfix-` prefix or under a folder called hotfix.

---

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

### Contributing Prerequisites

To replicate the setup used to initially create this repository you will need

1. Clone the Repo

   ```sh
   git clone https://github.com/RolfMoleman/Terraform-Latest.git
   ```

2. Install Chocolatey

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```

3. Install Node

   ```cmd
   choco install nodejs
   ```

4. Install Terraform

   ```cmd
   choco install terraform-latest
   ```

5. Install TFlint

   ```cmd
   choco install tflint
   ```

6. Install terraform-docs

   ```cmd
   choco install terraform-docs
   ```

7. Install Python

   ```cmd
   choco install python
   ```

8. Install pip

   ```cmd
   curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
   python get-pip.py
   ```

9. Install pre-commit

   ```cmd
   pip install pre-commit
   ```

10. Install vscode

    ```cmd
    choco install vscode
    ```

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- LICENSE -->

## License

Distributed under the MIT License. See [![LICENSE][license-url]][license-file]
for more information.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- CONTACT -->

## Contact

To contact me please use the discussion against the relevant release.
this can be found [here][discussions-url]

Project Link: [https://github.com/RolfMoleman/Terraform-Latest](https://github.com/RolfMoleman/Terraform-Latest)

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [jamestoyer](https://github.com/jamestoyer/)
  - for the repo [chocolatey-packages](https://github.com/jamestoyer/chocolatey-packages)
- [othneildrew](https://github.com/othneildrew)
  - for the repo [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
- [sabihsaleh](https://github.com/sabihsaleh) - for the inspiration to do this.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- BADGES AND SHIELDS -->

<!-- GITHUB LINKS -->

[contributors-shield]: https://img.shields.io/github/contributors/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[contributors-url]: https://github.com/RolfMoleman/Terraform-Latest/graphs/contributors
[discussions-url]: https://github.com/RolfMoleman/Terraform-Latest/discussions
[forks-shield]: https://img.shields.io/github/forks/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[forks-url]: https://github.com/RolfMoleman/Terraform-Latest/network/members
[stars-shield]: https://img.shields.io/github/stars/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[stars-url]: https://github.com/RolfMoleman/Terraform-Latest/stargazers
[issues-shield]: https://img.shields.io/github/issues/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[issues-url]: https://github.com/RolfMoleman/Terraform-Latest/issues
[license-shield]: https://img.shields.io/github/license/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[license-url]: https://github.com/RolfMoleman/Terraform-Latest/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/carlrdawson

<!-- IMAGES AND ICONS -->

[logo-image]: /.assets/logo.png
[product-screenshot]: /.assets/screenshot.png

<!-- MARKDOWN DOCUMENT LINKS -->
[license-file]: /LICENSE
<!-- PIPELINE LINKS -->
