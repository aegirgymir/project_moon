# 골목의 잔향 — 다운로드

Project Moon 세계관 기반의 비공식 팬 전투 프로토타입입니다.
해결사 4명과 조직원 4명의 위치 기반 턴제 전투를 플레이할 수 있습니다.
인물·장소·그래픽·전투 수치는 창작입니다.

## 다운로드

- [게임·수정 가능한 소스·조사 자료 ZIP 다운로드](downloads/afterimage-combat-v0.1.zip?raw=true)
- [설치 없이 실행하는 단일 HTML 다운로드](downloads/afterimage-combat.html?raw=true)
- [시작 안내](downloads/START-HERE.txt)
- [SHA-256 무결성 확인값](downloads/SHA256SUMS.txt)

GitHub 로그인이 필요한 저장소라면 로그인한 브라우저에서 다운로드하세요.
파일 보기 화면이 열리면 **Download raw file** 버튼을 누르세요.

## 플레이 방법

ZIP을 압축 해제한 뒤 `afterimage-combat/play/game.html`을 Chrome, Edge, Firefox 또는 Safari로 여세요.
HTML 파일만 내려받아 브라우저로 열어도 됩니다. 별도 설치나 서버·인터넷 연결이 필요하지 않습니다.
기술 카드 → 빛나는 대상 → 금색 실행 버튼 순서로 조작합니다.

`1`~`3`: 기술 / `←`·`→`: 대상 / `Enter`: 실행 / `M`: 이동 / `G`: 방어 / `W`: 대기.

## 소스와 조사 자료

ZIP 안 `source/` 폴더에 소스, 테스트, 잠금 파일, README와 개발 지침이 있습니다.
`source/docs/RESEARCH.md`는 세계관 근거와 검증 한계,
`source/docs/COMBAT.md`는 이 프로토타입의 실제 규칙을 기록합니다.
공식 사이트와 위키 직접 교차검증은 네트워크 제한으로 미완료입니다.

## 검증

- ZIP 무결성 및 ZIP 안 게임과 단일 HTML의 동일성 확인.
- 17개 규칙 테스트(100개 난수 초기값의 전체 전투 포함)와 프로덕션 빌드 통과.
- 단일 HTML을 네트워크 없이 Chromium에서 실행해 5라운드, 4명 생존 승리·재시작 확인.
- 브라우저 로컬 파일 URL 자체는 클라우드 정책으로 제한되어 HTML 문서를 직접 로드해 검증했습니다.

이 브랜치는 다운로드 배포용입니다. 기존 작업 디렉터리의 개발 파일과 분리하여 관리합니다.
