# ShiftLens Workspace

ShiftLens는 제조 현장의 교대조 인수인계와 설비 알림 대응을 제품화한 포트폴리오 프로젝트입니다.

## 저장소 구조

```text
shiftlens-workspace/
  shiftlens-fe/  # Next.js 교대조 운영 웹
  shiftlens-be/  # Flask + Tortoise ORM REST API
```

FE/BE는 Git submodule로 연결되어 있습니다.

## 프로젝트 링크

- FE: https://github.com/shiftlens-labs/shiftlens-fe
- BE: https://github.com/shiftlens-labs/shiftlens-be
- Personal mirror: https://github.com/cyjoon68/shiftlens-workspace

## 실행

```bash
git clone --recurse-submodules https://github.com/shiftlens-labs/shiftlens-workspace.git
```

## 포트폴리오 포인트

운영자가 실제 교대 상황에서 쓰는 handoff, alert, action, audit 흐름을 FE/BE로 분리해 구성했습니다.
