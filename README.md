# Installation

1. Download `vscodefix` and `pipenv_activation` scripts:

   [Latest `vscodefix` release](https://github.com/SupremeLobster/vscode-pipenv-integration-fix/releases/latest/download/vscodefix)
   
   [Latest `pipenv_activation` release](https://github.com/SupremeLobster/vscode-pipenv-integration-fix/releases/latest/download/pipenv_activation)

3. Copy both files to whatever directory you want, then add that directory to your PATH.

# Instructions

Whenever VSCode stops automatically launching new terminals with the Pipenv virtual environment already open (usually happens after a VSCode update), simply run:

```bash
vscodefix
```

from any WSL terminal, and the integration will start working again.

Now, any new terminal you open inside VSCode will automatically launch inside a Pipenv shell, as expected.
