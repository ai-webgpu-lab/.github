# ai-webgpu-lab/.github

[![CI](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/ci.yml)
[![Deploy GitHub Pages Demo](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/deploy-pages.yml/badge.svg?branch=main)](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/deploy-pages.yml)
[![Operations Status Check](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/operations-check.yml/badge.svg?branch=main)](https://github.com/ai-webgpu-lab/docs-lab-roadmap/actions/workflows/operations-check.yml)

`ai-webgpu-lab` 조직 전체에 적용되는 기본 커뮤니티 파일과 협업 규칙을 관리하는 저장소입니다. 각 개별 프로젝트에서 중복 관리하지 않아도 되도록 이슈 폼, PR 템플릿, 조직 프로필, 기본 리뷰 정책을 여기에서 통합 관리합니다.

## 저장소 역할
- 실험, 벤치마크, 앱, 인프라, 문서 저장소에 공통 적용되는 기본 협업 UX를 정의합니다.
- 조직 프로필과 공통 템플릿을 통해 저장소별 문서 품질과 리포팅 포맷을 일정 수준 이상으로 맞춥니다.
- 개별 저장소가 도메인 로직에 집중하도록 조직 차원의 기본 규칙을 분리합니다.

## 포함 내용
- `.github/ISSUE_TEMPLATE/` - 실험, 벤치, 인프라, 문서, 버그용 공통 이슈 폼
- `.github/pull_request_template.md` - 기본 PR 제출 형식
- `.github/CODEOWNERS` - 조직 기본 리뷰 책임자
- `profile/README.md` - 조직 메인 프로필 소개
- `CONTRIBUTING.md` - 조직 기본 운영 규칙

## 운영 원칙
- 저장소별 개별 폼보다 조직 공통 규칙을 우선하며, 예외가 필요하면 이유를 문서화합니다.
- 실험/벤치 저장소의 결과 리포팅 규칙은 `docs-lab-roadmap`의 계획 문서와 일치해야 합니다.
- 이 저장소의 변경은 조직 전체 UX에 영향을 주므로 문구 변경도 목적과 파급 범위를 명확히 남겨야 합니다.

## 조직 상태 대시보드
- 전체 repo/Pages 상태: `docs-lab-roadmap/docs/PAGES-STATUS.md`
- Actions/deploy/operations 상태: `docs-lab-roadmap/docs/WORKFLOW-STATUS.md`
- 통합 sketch/adapter 상태: `docs-lab-roadmap/docs/INTEGRATION-STATUS.md`
- sketch capabilities: `docs-lab-roadmap/docs/SKETCH-METRICS.md`
- 조직 프로필은 `.github/profile/README.md`에서 관리합니다.

## 갱신 기준
- 새 저장소 유형이 추가되면 대응 이슈 폼 또는 템플릿을 함께 추가합니다.
- 리뷰 흐름이 바뀌면 `CODEOWNERS`, PR 템플릿, 조직 프로필을 함께 갱신합니다.
- 마스터 플랜과 맞지 않는 템플릿은 유지하지 않습니다.

## 관련 저장소
- `docs-lab-roadmap` - 조직 운영 계획과 부트스트랩 기준 문서
- `shared-github-actions` - 공통 CI 재사용 자산
- `shared-bench-schema` - 결과 리포팅 공통 스키마

## 라이선스
MIT
