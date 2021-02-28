# Devcontainer
Devcontainer is a Visual Studio Code technology for creating development cointainers with great IDE support. Allows auto configure extensions and port forwarding.

## Installation

1. Install Visual Studio Code extensions:

    - Docker https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
    - Remote Containers https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

2. Copy devcontainer.dist.json as a devcontainer.json.

## Run

Press *F1* and choose *Remote-Containers: Reopen in Container*.

First run it can take few minutes because there is a docker container downloading and building.

Next time you can just open folder from VSC list and this will be automatically open inside container.

## References

https://code.visualstudio.com/docs/remote/devcontainerjson-reference