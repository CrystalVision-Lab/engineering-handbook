# CrystalVision-Lab Engineering Handbook

SiC XRT 분석 프로젝트의 공통 개발 규칙입니다. 모든 Agent와 기여자는 **자신이 작업하는 저장소의 `AGENTS.md`를 먼저 읽고**, 이 저장소의 [AI_AGENT_RULES.md](AI_AGENT_RULES.md), [저장소 경계](REPOSITORY_BOUNDARIES.md), [기여 절차](CONTRIBUTING.md)를 따릅니다.

| 저장소 | 책임 |
| --- | --- |
| [sic-xrt-analyzer](https://github.com/CrystalVision-Lab/sic-xrt-analyzer) | PySide6/QML 사용자 앱, XRT 시각화·분석, 추론 |
| [sic-xrt-ml](https://github.com/CrystalVision-Lab/sic-xrt-ml) | 모델 연구·학습·평가·ONNX 내보내기 |
| [sic-xrt-data-tools](https://github.com/CrystalVision-Lab/sic-xrt-data-tools) | TIFF 검사·타일링·메타데이터·주석 변환·데이터셋 검증 |

작업 흐름: **GitHub Issue → 해당 저장소의 브랜치 → 기능 단위 커밋 → PR → CI/리뷰 → 병합**. 커밋 제목은 `feat: 한글 설명` 형식입니다. 다른 저장소의 코드는 해당 저장소의 별도 Issue/PR 없이 수정하지 않습니다.

이 문서는 정책의 원본입니다. 각 저장소의 `AGENTS.md`에는 작업 시 반드시 지킬 핵심 규칙을 복제해 단독으로도 읽을 수 있게 합니다.
