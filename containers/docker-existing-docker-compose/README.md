# Existing Docker Compose (Extend)

## Summary

*Illustrates how you can reuse an existing docker-compose.yml for your dev container.*

| Metadata | Value |  
|----------|-------|
| *Contributors* | The VS Code team |
| *Definition type* | Docker Compose |
| *Languages, platforms* | Any |

> **Note:** There is also a single [Dockerfile](../docker-existing-dockerfile) variation of this same definition.

## Usage

First, install the **[Visual Studio Code Remote Development](https://aka.ms/vscode-remote/download/extension)** extension pack if you have not already.

To use the definition with an existing project that contains a `docker-compose.yml` file:

1. Copy the `.devcontainer` folder into your project root.
2. Modify the `.devcontainer/dev-container.yml` and `devcontainer.json` files as needed (see comments)
2. Reopen the folder in the container (e.g. using the **Remote-Container: Reopen Folder in Container** command in VS Code) to use it unmodified.

If you prefer, you can look through the contents of the `.devcontainer` folder to understand how to make changes to your own project.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the MIT License. See [LICENSE](../../LICENSE). 