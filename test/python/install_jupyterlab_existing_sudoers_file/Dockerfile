# Builds an image with a preconfigured SUDOERS file
# Used to test the install script for JupyterLab which modifies this file
FROM mcr.microsoft.com/devcontainers/base:focal

COPY --chown=root sudoers.test /etc/sudoers.d/vscode
