# Scoutflo Helm Charts Collection

This repository contains a collection of Helm charts for various applications. Helm is a package manager for Kubernetes that helps you manage and deploy applications and services on Kubernetes clusters.

## Available Charts

- [airbyte](link-to-chart-1)
- [cerbos](link-to-chart-2)
- [elasticsearch](link-to-chart-3)
- [flagsmith](link-to-chart-4)
- [zammad](link-to-chart-5)
- ...

## Usage

To use one of the charts in this repository, follow these steps:

1. Add the Helm chart repository to your local repositories:

   ```bash
   helm repo add <repo-name> <repo-url>
   ```

2. Update the Helm repositories:

   ```bash
   helm repo update
   ```

3. Install the desired chart:

   ```bash
   helm install <release-name> <repo-name>/<chart-name>
   ```

   Replace `<release-name>` with the name you want to give to the release, `<repo-name>` with the name you assigned to the repository in step 1, and `<chart-name>` with the name of the chart you want to install.

   You can also customize the installation by providing additional options and values. Refer to the individual chart's documentation for more information.

## Contributing

Feel free to contribute to this repository! Contributions are welcome and encouraged. Here's how you can contribute:

1. Fork this repository.
2. Create a new branch for your contribution: `git checkout -b my-contribution`.
3. Make your changes and commit them: `git commit -am 'Add some contribution'`.
4. Push your changes to your fork: `git push origin my-contribution`.
5. Open a Pull Request (PR) in this repository, describing your changes and the reasoning behind them.

Please ensure that your contributions adhere to the guidelines and best practices for Helm chart development. If you have any questions or need assistance, feel free to open an issue in this repository.
