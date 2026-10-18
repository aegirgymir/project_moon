# 골목의 잔향 v0.4 — 실제 LCB 기본 인격 스프라이트

《림버스 컴퍼니》 수감자 12명 중 4명을 편성하는 비공식 턴제 전투 프로토타입입니다.

## 다운로드

- **[v0.4 게임·소스·이미지 출처 ZIP](downloads/afterimage-combat-v0.4.zip?raw=true)**
- **[v0.4 단일 HTML](downloads/afterimage-combat-v0.4.html?raw=true)**
- [시작 안내](downloads/START-HERE-v0.4.txt) · [SHA-256](downloads/SHA256SUMS-v0.4.txt)

ZIP을 풀고 `afterimage-combat-v0.4/play/game.html`을 브라우저로 여세요. HTML 하나만 받아도 됩니다. 설치·서버·인터넷 연결은 필요하지 않습니다. 파일 보기 화면이 열리면 **Download raw file**을 누르세요.

## 반영 내용

- 12명의 팬 모델을 LCB 기본 인격의 실제 인게임 대기 스프라이트로 교체했습니다.
- 전장·초상화·편성창·클로즈업에서 같은 이미지를 사용하고 몸 크기·발 위치를 맞췄습니다.
- 고유 스킬 4개, 대사 제거, 행동 클로즈업·피격·지원·모션 감소를 유지했습니다.
- 12장의 WebP를 HTML에 내장했습니다. ZIP에는 수정 가능한 전체 소스와 이미지·출처 문서가 포함됩니다.

확보한 자산은 커뮤니티 보관본의 **대기 자세 1장씩**입니다. 보관본 WebP는 수정하지 않았으며 권리는 Project Moon에 있습니다. 원작의 전체 공격 애니메이션·골격은 포함하지 않습니다. 돌진·피격·카메라와 전투 규칙·4개 기술은 프로토타입의 각색입니다.

출처: [eldritchtools/limbus-assets, 고정 커밋 4b6cb07](https://github.com/eldritchtools/limbus-assets/tree/4b6cb07b3a2608a2f4c59dfe08ce1a41bc16d7c0/assets/identities). 자세한 내역과 파일별 해시는 ZIP의 `source/docs/ASSETS.md`, `source/src/assets/lcb/manifest.json`에 있습니다. 게임 설치본과의 독립 대조 검증은 완료하지 않았습니다.

## 검증

자동 테스트 32개 통과(100개 난수 초기값 전투·12명 인격 연결·이미지 해시 포함), 프로덕션 빌드 성공. 실제 Chromium에서 개발 서버와 네트워크를 끈 단일 HTML 모두 스프라이트 12장 디코딩·편성·고유 스킬 4개·양측 클로즈업을 확인했습니다. 360/390/768/1024/1440px와 모션 감소를 통과했고 5라운드·4명 생존으로 승리했습니다. JS 런타임 오류가 없었습니다. 클라우드의 file:// 탐색 제한 때문에 오프라인 HTML 직접 렌더링 검증과 실제 파일 URL 탐색은 구분합니다.

## 이전 버전

- [v0.3 ZIP](downloads/afterimage-combat-v0.3.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.3.html?raw=true)
- [v0.2 ZIP](downloads/afterimage-combat-v0.2.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.2.html?raw=true)
- [v0.1 ZIP](downloads/afterimage-combat-v0.1.zip?raw=true) · [HTML](downloads/afterimage-combat.html?raw=true)

이전 파일과 다운로드 브랜치는 보존했습니다.
