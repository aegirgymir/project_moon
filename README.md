# 골목의 잔향 v0.5 — 실제 기본 인격 공격 모션

《림버스 컴퍼니》 수감자 12명 중 4명을 편성하는 비공식 턴제 전투 팬 프로토타입입니다.

## 다운로드

- **[v0.5 게임·소스·출처 ZIP](downloads/afterimage-combat-v0.5.zip?raw=true)**
- **[v0.5 단일 HTML](downloads/afterimage-combat-v0.5.html?raw=true)**
- [시작 안내](downloads/START-HERE-v0.5.txt) · [SHA-256](downloads/SHA256SUMS-v0.5.txt)

ZIP을 풀고 `afterimage-combat-v0.5/play/game.html`을 브라우저로 여세요. HTML 파일 하나만 받아도 됩니다. 설치·서버·인터넷 연결이 필요하지 않습니다. 파일 보기 화면에서는 **Download raw file**을 누르세요.

## 달라진 전투 연출

- 기본 인격 12명의 **실제 공격 모션 3종씩, 총 36종**을 반영했습니다.
- 정지 그림을 움직이던 연출을 실제 공격 준비·베기·찌르기·강타·복귀 프레임으로 교체했습니다.
- 프레임마다 다른 표시 시간, 무기 궤적, 좌우 반전, 알파와 레이어 순서를 사용합니다.
- 실제 타격 자세에 카메라 충격·피해 숫자·피격/회피를 맞췄습니다. 이미지 로딩 뒤 재생을 시작하고 프레임·카메라를 같은 시계로 처리합니다.
- 기본 인격의 대기·이동·방어·회피·피격 자세 60종도 포함합니다. 지원 효과는 이 게임의 각색입니다.
- 빠른 재생·건너뛰기·재시작·모션 감소, 고유 스킬 4개·대사 제거·12명 편성을 유지했습니다.

공개 [Limbus Archive](https://limbus-archive.com)의 원작 자산 추출본에서 공격 클립과 이미지 367개를 확보했습니다. 이미지·원본 클립 JSON을 보존하고 파일별 SHA-256과 출처를 기록했습니다. 자산 권리는 Project Moon에 있습니다. 원작 Unity 실행 모델·음원·음성·절차적 이펙트 전체를 이식한 것은 아닙니다. 전투 규칙과 기술 연결은 각색입니다.

확보 범위와 넓힌 자료 조사, 기술별 모션 연결은 ZIP의 `source/docs/ASSETS.md`, `source/docs/ATTACK-MOTION.md`에 있습니다. 독립적인 원작 설치본 대조는 완료하지 않았습니다.

## 검증

자동 테스트 **37개** 통과, 프로덕션 빌드 성공. 실제 Chromium에서 공격 36종의 프레임 변화와 이미지 367개 디코딩을 확인했습니다. 패키징 때 모든 이미지의 내장 바이트 해시를 검증합니다.

개발 서버와 네트워크를 끈 단일 HTML 모두 실제 전투·양측 연출·프레임 교체·카메라·건너뛰기·재시작을 통과했고, 5라운드·수감자 4명 생존으로 승리했습니다. 360/390/768/1024/1440px와 모션 감소 검증 통과, JS 런타임 오류 없음. 클라우드의 file:// 탐색 제한 때문에 오프라인 HTML 직접 렌더링 검증과 실제 파일 URL 탐색은 구분합니다.

## 이전 버전

- [v0.4 ZIP](downloads/afterimage-combat-v0.4.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.4.html?raw=true)
- [v0.3 ZIP](downloads/afterimage-combat-v0.3.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.3.html?raw=true)
- [v0.2 ZIP](downloads/afterimage-combat-v0.2.zip?raw=true) · [HTML](downloads/afterimage-combat-v0.2.html?raw=true)
- [v0.1 ZIP](downloads/afterimage-combat-v0.1.zip?raw=true) · [HTML](downloads/afterimage-combat.html?raw=true)

이전 버전의 파일과 다운로드 브랜치는 보존했습니다.
