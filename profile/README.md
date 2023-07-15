# Project New Caledonia 에 어서오세요!!

본 프로젝트는 DetectiveCrow의 나만의 서버 만들기 프로젝트입니다.

프로젝트에서는 주로 Kubernetes로 개인 서버를 구축하고 해당 서버에 다양한 서비스를 설치, 유지하는 것에 대한 내용을 보관할 것입니다. 

# Project Rules

## Commit Convention

본 조직 내의 레파지토리는 모두 conventional commit을 사용하고 있습니다.

아래와 같은 형식으로 commit message를 작성하며 주십시오.
더 자세한 내용은 https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional 에서 확인할 수 있습니다.

```
<type>(<scope>): <short summary> (<ticket number>)
  │       │             │         │
  │       │             │         └─⫸ 프로젝트 관리 툴의 티켓 번호, TEST-123, PROJ-456등의 형식으로 해당 커밋이 어떠한 티켓과 연관이 있는지 작성합니다.
  │       │             └─⫸ 명령문, 현재 시제로 작성합니다. 대문자를 사용하지 않으며, 마침표로 끝내지 않습니다.
  │       │
  │       └─⫸ Commit Scope: 영향을 미치는 범위, 모듈, 라이브러리 등
  │
  └─⫸ Commit Type: build | chore | ci | docs | feat | fix | perf | refactor | revert | style | test
<type>과 <summary> 필드는 필수 항목이며, (<scope>)와 (<ticket number>) 필드는 선택사항입니다.
```

`(<ticket number>)` 필드의 경우, 선택사항이지만 아래의 링크에 설명된 Autolink 설정을 해주면 코드의 변경점을 쉽게 트래킹 할 수 있으므로 가능하면 사용하는 것을 권장드립니다.
