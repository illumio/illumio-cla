# Illumio CLA Tracker

This repository acts as a central hub for all Illumio CLA signatures. It leverages the [SAP CLA assistant](https://github.com/contributor-assistant/github-action) GitHub actions workflow to embed the CLA signing into the PR process for Illumio repositories. This serves to automate and store CLA signatures in an accessible, central location.  

## Getting Started

For new projects in the Illumio organization, copy the CLA workflow from `workflows/cla.yml` and make the necessary adjustments to point to this repository.  

Enable branch protection as needed and create a repo-scoped [Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) per the [CLA assistant instructions](https://github.com/marketplace/actions/cla-assistant-lite).  

