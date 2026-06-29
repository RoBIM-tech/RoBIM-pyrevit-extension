# RoBIM pyRevit Extension Source

This repository only publishes the pyRevit Extension Manager source metadata.

The actual RoBIM extension repository is:

```text
https://github.com/gagaggan/RoBIM-pyrevit.git
```

## Register In pyRevit

Run this once:

```powershell
pyrevit extensions sources add https://raw.githubusercontent.com/gagaggan/RoBIM-pyrevit-extension/main/extensions.json
```

Then search for RoBIM:

```powershell
pyrevit extensions search RoBIM
```

If the RoBIM repository is private, use your GitHub username and a Personal Access Token when pyRevit asks for credentials.

```text
Username: gagaggan
Password: GitHub Personal Access Token
```

## Install Directly

```powershell
pyrevit extend ui RoBIM https://github.com/gagaggan/RoBIM-pyrevit.git --branch=main
```

## Update

```powershell
pyrevit extensions update RoBIM
pyrevit caches clear --all
```
