# Docs-as-code Dev Container Starter Template

Copy/clone this repository to get started with a VS Code dev container with everything required to start writing docs-as-code.

## Getting Started

Install [Visual Studio Code](https://code.visualstudio.com/Download) along with the following extension(s)

> NOTE: you will be prompted to install these recommended extensions when opening the repo in VS Code for this first time

- [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

### Option 1: Copy and clone using GitHub templates

TODO:

### Option 2: Copy and clone using Visual Studio Code

- Open Visual Studio Code
- From the command palette (Ctrl/Cmd+Shift+P) select `Git: Clone` and choose `Clone from GitHub`
- Type the URL of this repo e.g. https://github.com/danlewisao/docs-as-code-dev-container-template

### Open the Dev Container

Once cloned locally and opened in Visual Studio Code:

- Open the command palette (Ctrl/Cmd+Shift+P) and select `Remote-Containers: Reopen in Container`

> NOTE: VS Code may prompt to open in the dev container as it will detect the .devcontainer directory

The dev container might take a few minutes to initialise, but this only happen once per clone.

Once inside the dev container, create some new architecture documentation using a template via the pre-installed
`copier` template engine e.g.

```bash
$ copier gl:djjlewis/templates ./architecture

Project name: 
```

`cd` into the `architecture` directory and type `build-docs.sh`.

You should see the compiled architecture documents under the `generated` folder