# Results

## 1. 실험 요약
- 저장소: .github
- 커밋 해시: 8e95e51
- 실험 일시: 2026-05-20T15:33:48.268Z -> 2026-05-20T15:33:48.268Z
- 담당자: ai-webgpu-lab
- 실험 유형: `infra`
- 상태: `success`

## 2. 질문
- 조직 공통 issue/PR/profile/CONTRIBUTING/RESULTS-template inventory가 deterministic 결과 문서로 고정되는가
- issue 폼 수, profile 섹션 수, codeowners 존재 여부 등 community surface 지표가 같은 결과 스키마로 기록되는가
- 조직 템플릿이 변할 때 fixture와 readiness baseline이 같이 움직이는 운영 체계를 유지할 수 있는가

## 3. 실행 환경
### 브라우저
- 이름: Chrome
- 버전: 147.0.7727.15

### 운영체제
- OS: Linux
- 버전: unknown

### 디바이스
- 장치명: Linux x86_64
- device class: `desktop-high`
- CPU: 16 threads
- 메모리: 32 GB
- 전원 상태: `unknown`

### GPU / 실행 모드
- adapter: n/a (org template audit)
- backend: `webgpu`
- fallback triggered: `false`
- worker mode: `main`
- cache state: `warm`
- required features: []
- limits snapshot: {}

## 4. 워크로드 정의
- 시나리오 이름: .github Community Audit
- 입력 프로필: org-template-surface
- 데이터 크기: issue-forms=5; community-files=6; profile-sections=4; contributing-sections=3; codeowners=true; automation=playwright-chromium
- dataset: dotgithub-community-v1
- model_id 또는 renderer: audit-18-items
- 양자화/정밀도: -
- resolution: -
- context_tokens: -
- output_tokens: -

## 5. 측정 지표
### 공통
- time_to_interactive_ms: 1742.4 ms
- init_ms: 7.2 ms
- success_rate: 1
- peak_memory_note: n/a (org template audit)
- error_type: -

### Org / Infra
- baseline_readiness_score: 107
- issue_form_count: 5
- community_file_count: 6
- profile_section_count: 4
- contributing_section_count: 3
- coverage_pct: 100 %
- codeowners states: true
- backends: webgpu

## 6. 결과 표
| Run | Scenario | Backend | Cache | Mean | P95 | Notes |
|---|---|---:|---:|---:|---:|---|
| 1 | .github Community Audit | webgpu | warm | 107 | 100 | issue_forms=5, community_files=6, codeowners=true |

## 7. 관찰
- playwright-chromium로 수집된 automation baseline이며 headless=true, browser=Chromium 147.0.7727.15.
- 실제 runtime/model/renderer 교체 전 deterministic harness 결과이므로, 절대 성능보다 보고 경로와 재현성 확인에 우선 의미가 있다.

## 8. 결론
- 첫 raw result와 summary 문서가 연결됐다.
- 다음 단계는 deterministic harness를 실제 workload로 교체하는 것이다.
- 브라우저와 cache-state 반복 측정이 더 필요하다.

## 9. 첨부
- 스크린샷: ./reports/screenshots/01-dotgithub-community-baseline.png
- 로그 파일: ./reports/logs/01-dotgithub-community-baseline.log
- raw json: ./reports/raw/01-dotgithub-community-baseline.json
- 배포 URL: https://ai-webgpu-lab.github.io/.github/
- 관련 이슈/PR: -
