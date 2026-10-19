# 골목의 잔향 v0.6 — 스킬 모션·효과·상태 툴팁

《림버스 컴퍼니》 기본 인격 수감자 12명 중 4명을 편성하는 비공식 턴제 전투 팬 프로토타입입니다.

## 다운로드

- **[v0.6 게임·소스·문서 ZIP](downloads/afterimage-combat-v0.6.zip?raw=true)**
- **[v0.6 단일 HTML](downloads/afterimage-combat-v0.6.html?raw=true)**
- [시작 안내](downloads/START-HERE-v0.6.txt) · [SHA-256](downloads/SHA256SUMS-v0.6.txt)

ZIP을 풀고 `afterimage-combat-v0.6/play/game.html`을 브라우저로 여세요. HTML 하나만 받아도 됩니다. 설치·서버·인터넷 연결이 필요하지 않습니다. 파일 보기 화면에서는 **Download raw file**을 누르세요.

## 요청 반영

- **스킬에 맞는 모션**: 원본 프레임을 검토해 스킬별 클립/구간을 고정했습니다. 지원형의 순번별 모션 순환을 제거하고, 관통·횡베기·내려치기·방패 돌진 등을 구분했습니다. 설명도 실제 무기에 맞췄습니다.
- **타격 동기화**: 첫 프레임 변화라는 추정을 개별 타격 신호로 대체하고 긴 대기를 줄였습니다. 하나의 시계가 모션·카메라·이펙트·피격·효과음·결과·종료를 구동합니다. 체력·스트레스 패널도 결과 시점에 갱신합니다.
- **컨셉 이펙트**: 출혈 절개, 칼날 투사, 관통선, 충격파, 파도, 방패, 회복, 안정, 조준 표식 등을 실제 대상 몸에 배치했습니다. 빗나감에는 명중 효과를 내지 않습니다.
- **상태 툴팁**: 전장·수감자/대상 패널의 아이콘에 마우스를 올리면 효과와 남은 횟수·보호자·해제 조건을 표시합니다. 모바일 탭과 정보 패널의 키보드 포커스도 지원합니다. 아이콘 클릭은 행동을 소모하지 않습니다.
- 기존 기본 인격 원본 자산, 고유 스킬 4개, 대사 제거, 편성과 오프라인 실행을 유지했습니다. 전투 수치는 변경하지 않았습니다.

출혈은 중첩마다 다른 잔여 횟수를, 표식은 남은 명중 횟수를 표시합니다. 보호/방어/엄호, 동요, 빈사의 규칙도 설명합니다. 즉시 회복 효과를 가상의 지속 버프로 표시하지 않습니다.

## 검증

자동 테스트 **40개** 통과, 프로덕션 빌드 성공. 실제 원본 이미지를 사용해 스킬 48개 × 두 속도인 **96개 조합과 146개 타격 신호**를 검사했습니다. 실제 전투에서 체력 표시 시점, 출혈·표식·보호 툴팁, 모바일 탭을 확인했습니다.

네트워크를 끈 단일 HTML에서 실제 전투 승리·호버·동기화·건너뛰기·재시작·360/390/768/1024/1440px·모션 감소를 검증했습니다. 5라운드·4명 생존·28회 행동, JS 오류 없음. 패키징 때 원본 이미지 367개 모두의 내장 바이트 해시를 검증합니다. 클라우드의 file:// 탐색 제한 때문에 오프라인 HTML 직접 렌더링과 실제 파일 URL 탐색은 구분합니다.

기본 인격 이미지/공격 클립의 권리는 Project Moon에 있습니다. 커뮤니티 추출본에서 확보한 원본 바이트는 보존하고, 표시 구간·시간·타격 신호·추가 효과와 전투 규칙은 이 프로토타입에 맞춰 각색했습니다. 출처·한계·구현 및 검증 설명은 ZIP의 `source/docs/ASSETS.md`, `source/docs/ATTACK-MOTION.md`에 있습니다.

## 이전 버전

- [v0.5 ZIP](downloads/afterimage-combat-v0.5.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.5.html?raw=true)
- [v0.4 ZIP](downloads/afterimage-combat-v0.4.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.4.html?raw=true)
- [v0.3 ZIP](downloads/afterimage-combat-v0.3.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.3.html?raw=true)
- [v0.2 ZIP](downloads/afterimage-combat-v0.2.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.2.html?raw=true)
- [v0.1 ZIP](downloads/afterimage-combat-v0.1.zip?raw=true) · [HTML](downloads/afterimage-combat.html?raw=true)

이전 파일과 다운로드 브랜치는 보존했습니다.
