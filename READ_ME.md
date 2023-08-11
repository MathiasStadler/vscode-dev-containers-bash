# Target of project open a bash shell inside a vscode dev-container

## vscode version

```bash
code --version
1.81.1
6c3e3dba23e8fadc360aed75ce363ba185c49794
x64
6c3e3dba23e8fadc360aed75ce363ba185c49794
x64
```

## list extension

```bash
code --list-extensions  --show-versions 
```

Anjali.clipboard-history@1.0.7
belfz.search-crates-io@1.2.1
DavidAnson.vscode-markdownlint@0.51.0
donjayamanne.python-environment-manager@1.0.4
esbenp.prettier-vscode@10.1.0
formulahendry.code-runner@0.12.0
foxundermoon.shell-format@7.2.5
jock.svg@1.5.3
MS-CEINTL.vscode-language-pack-de@1.81.2023080209
ms-python.isort@2023.10.1
ms-python.python@2023.14.0
ms-python.vscode-pylance@2023.8.20
ms-toolsai.jupyter@2023.7.1002162226
ms-toolsai.jupyter-keymap@1.1.2
ms-toolsai.jupyter-renderers@1.0.17
ms-toolsai.vscode-jupyter-cell-tags@0.1.8
ms-toolsai.vscode-jupyter-slideshow@0.1.5
ms-vscode-remote.remote-containers@0.304.0
ms-vscode-remote.remote-ssh@0.102.0
ms-vscode-remote.remote-ssh-edit@0.86.0
ms-vscode-remote.remote-wsl@0.81.0
ms-vscode-remote.vscode-remote-extensionpack@0.24.0
ms-vscode.remote-explorer@0.4.1
ms-vscode.remote-server@1.4.0
mutantdino.resourcemonitor@1.0.7
rust-lang.rust-analyzer@0.3.1615
streetsidesoftware.code-spell-checker@2.20.5
tamasfe.even-better-toml@0.19.2
tomoki1207.pdf@1.2.2
usernamehw.errorlens@3.13.0
vadimcn.vscode-lldb@1.9.2

[Developing inside a Container getting-started](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started)

## check docker is already installed

```bash
docker --version
#Docker version 24.0.5, build ced0996
```

- [if docker not installed via this tutorial](https://docs.docker.com/engine/install/ubuntu/)

## [set up consistent line endings](https://code.visualstudio.com/docs/remote/troubleshooting#_resolving-git-line-ending-issues-in-wsl-resulting-in-many-modified-files)

- very useful

## create a dev-container am existing folder in a container

[tutorial from here](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started)

- Tip: If you want to edit the container's contents or settings before opening the folder, you can run Dev Containers: Add Dev Container Configuration Files... instead

1. press [F1] and paste ```Dev Containers: Add Dev Container Configuration Files``` in
2. select your dev-container type/version => ubuntu for example
3. chose additional futures
4. start the container => press [F1] and choose => "Dev Containers: OpenFolder in Container"
5. select the project folder in the new windows
6. open log and show the progress
