# RoBIM pyRevit Extension Source

This repository only publishes the pyRevit Extension Manager source metadata.

The actual RoBIM extension repository is:

```text
https://github.com/RoBIM-tech/RoBIM-pyrevit.git
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
pyrevit extend ui RoBIM https://github.com/RoBIM-tech/RoBIM-pyrevit.git --branch=main
```

## Update

```powershell
pyrevit extensions update RoBIM
pyrevit caches clear --all
```

## 처음 참여하는 개발자

새 Revit 버튼은 이 확장 등록 저장소에 만들지 않습니다. [Workspace 시작 안내](https://github.com/RoBIM-tech/RoBIM-Workspace/blob/main/START_HERE.md)와 신규 Native 버튼 제작 규칙을 따르세요. 이 저장소는 기존 pyRevit 확장 소스 메타데이터만 제공합니다. 기존 등록 사용자는 변경 전 pyRevit 소스 설정과 업데이트 경로를 확인하세요.
