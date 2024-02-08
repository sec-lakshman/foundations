# foundations

Qualys WAS GitHub Action
Description

GitHub Action for WAS allows DevOps teams to build Web application vulnerability scans into their existing GitHub workflows. By integrating and automating scans, web application security testing is accomplished early in the SDLC to catch and eliminate security flaws before they reach production.

This README document explains how to use the Qualys WAS GitHub Action and gives some samples for your reference.
How to use the Qualys WAS GitHub Action

    Visit GitHub configuration a workflow to enable GitHub Action in your repository.
    Subscribe to Qualys WAS module and obtain Qualys credentials.
    Create GitHub Secrets and variables. Refer to GitHub Action Parameter section below to learn about the parameters. Refer to Encrypted secrets for more details on how to set up secrets.
    Configure your workflow. In the actions steps of run.yaml file use Qualys/github_action_qwas@main
    You can use the Input Parameters to customize GitHub Action as per your requirements.

Note: The actions/checkout step is required to run before the scan action, otherwise the action does not have access to the Web apps to be scanned.
