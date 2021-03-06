# template-nuxt-ts
[![LICENSE](https://img.shields.io/github/license/tsunematsu21/template-nuxt-ts?color=green)](LICENSE)
![TEMPLATE](https://img.shields.io/badge/template-nuxt--ts-blue)

A template repository for [Nuxt TypeScript](https://typescript.nuxtjs.org/).

## Pre-requisites

When develop in container with *VS Code* :
* **[Visual Studio Code](https://code.visualstudio.com/) (a.k.a. VS Code)**  
  A modern source-code editor developed by Microsoft.
* **[Visual Studio Code Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)**  
  An extension of *VS Code* for use a Docker container as a full-featured development environment.  
  See [documentation](https://code.visualstudio.com/docs/remote/containers) for installation.
* **[Docker](https://www.docker.com/)**  
  A container platform. Required for the above extension.

When develop in local :
* **[Node.js](https://nodejs.org/)**  
  A JavaScript runtime.
* **[Yarn](https://yarnpkg.com/)**  
  A package manager for JavaScript.

## Getting started

When develop in container with *VS Code* :
* First, run the `Remote-Containers: Open Folder in Container...` command from VS Code Command Palette.

In either case :
* Run the following command depending on the situation.
  ```bash
  # Install dependencies
  yarn install

  # Serve with hot reload at localhost:3000
  yarn dev

  # Lint check
  yarn lint

  # Build for production and launch server
  yarn build
  yarn start

  # Generate static project
  yarn generate
  ```
