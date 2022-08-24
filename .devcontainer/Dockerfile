# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.194.0/containers/typescript-node/.devcontainer/base.Dockerfile

# [Choice] Node.js version: 16, 14, 12
ARG VARIANT="14"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Install Azure CLI
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

# Install Azure Static Web Apps CLI
RUN yarn global add @azure/static-web-apps-cli

# Install Azure Functions Core Tools V3.
RUN yarn global add azure-functions-core-tools@3
