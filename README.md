# ispacecraft

작은 우주선을 타고 우주를 탐사하는 브라우저 기반 3D 프로젝트입니다. 선내를 걷고, 우주 유영을 하고, 직접 조종하거나 AI 항법으로 행성·소행성·정거장을 오가며 자원을 관리할 수 있습니다.

**[지금 플레이하기](https://ispacecraft.com)** · [처음 시작하기](docs/getting-started.md) · [전체 안내](docs/README.md) · [현재 범위](docs/project-status.md) · [공개 로드맵](docs/roadmap.md) · [버그 신고와 제안](https://github.com/birdea/ispacecraft-info/issues)

현재 개발 중입니다. 기능과 조작은 업데이트될 수 있으므로 실행 중인 앱의 안내·키 지도·버전 표시를 함께 확인해 주세요.

## 무엇을 할 수 있나요

| 영역 | 주요 기능 |
|---|---|
| 이동과 비행 | 선내 이동, 우주 유영, 관성 비행, AI 항법, 궤도 이동, 대기권 진입과 자동 착륙 |
| 탐사와 자원 | 행성 지형 탐사, 광석·물 채굴, 연료·산소·식량·물 관리 |
| 정거장 | 도킹, 거래, 정비와 업그레이드 |
| 싱글 플레이 | 첫 항해 가이드와 튜토리얼, 태양계, 함대전 탈출·고물상·구조선 캠페인 |
| 같이 하기 | 방 코드와 방장 승인으로 참가하는 P2P 협동 |
| 조종과 생활 | 조종 계기판, 네비게이션, AI 패드, 도움 기능, 음악·미디어 재생 |
| 캐릭터 | 우주복·체형·얼굴 꾸미기, 사진의 특징을 이용한 카툰 얼굴 생성 |
| 항해와 보관 | 실제 태양계의 지원 항로에서 궤도 전이, 정거장 공유 창고와 장비 보관 |
| 감상 | 태양계 항해·채굴·착륙 등을 감상하는 화면 보호기 |

자세한 내용은 [기능 소개](docs/features.md)와 [캠페인 안내](docs/campaigns.md)를 참고하세요.

## 항해의 흐름

몸과 우주선 상태를 확인하고 목표를 정합니다. 직접 조종하거나 AI 항법으로 이동해 광석과 물을 확보하고, 필요한 만큼 변환해 생존과 비행에 사용합니다. 정거장에서 남은 광석을 거래하고 수리·업그레이드·보관을 거쳐 다시 출발합니다.

돌아올 연료를 남길지, 광석을 써서 더 멀리 갈지, 장비를 맡길지 선택하는 과정이 항해를 이룹니다. [항해와 생존의 흐름](docs/gameplay-loop.md)에 기본 순환을 정리했습니다.

## 시작하기

1. [ispacecraft.com](https://ispacecraft.com)을 엽니다.
2. 처음에는 도움 기능을 켜고 튜토리얼 또는 첫 항해 안내를 따라가 보세요.
3. 선내 이동과 조종석 탑승을 익힌 뒤 가까운 목표까지 비행해 봅니다.
4. 채굴·정거장 이용을 익히고, 진행을 남기려면 저장과 내보내기를 확인하세요.

데스크톱에서는 키보드·마우스, 터치 기기에서는 화면 스틱과 행동 버튼을 사용합니다. 브라우저는 WebGL과 Web Locks를 지원해야 합니다. 모바일에서는 기기 성능에 맞춰 그래픽 품질을 조절할 수 있습니다.

## 더 자세히 알아보기

| 관심 있는 내용 | 안내 |
|---|---|
| 처음 플레이 | [시작하기](docs/getting-started.md) · [조작](docs/controls.md) · [화면과 도움 기능](docs/guides/interface.md) |
| 몸과 우주선 | [생존](docs/guides/survival.md) · [우주선과 선내 이동](docs/guides/spacecraft.md) |
| 비행과 탐사 | [항법](docs/guides/navigation.md) · [태양계](docs/guides/solar-system.md) · [착륙과 지표](docs/guides/planet-exploration.md) |
| 자원과 귀환 | [채굴](docs/guides/mining.md) · [정거장과 공유 창고](docs/guides/stations-and-vault.md) |
| 함께하는 항해 | [같이 하기](docs/guides/co-op.md) · [캐릭터와 내 얼굴](docs/guides/character.md) |
| 세계와 원칙 | [세계관](docs/world-and-story.md) · [물리와 축척](docs/concepts/physics-and-scale.md) · [개발 접근](docs/development-approach.md) |

## 저장 안내

진행과 설정은 현재 기기·브라우저에 저장됩니다. 기기 간 자동 동기화는 제공하지 않습니다. 중요한 진행은 저장 파일로 내보내 보관하세요. 캠페인별 저장 범위와 내보내기에 포함되는 데이터는 [저장과 데이터 안내](docs/saving-and-data.md)에 정리했습니다.

## 앞으로의 방향

먼저 태양과 태양계 행성을 실사에 가깝게 표현하고, 완성도를 높인 뒤 약한 카툰 쉐이딩으로 앱 분위기를 맞추려 합니다. 광원·지형 디테일·블랙홀, 실제 탐색 대상으로 이어지는 별, 인공위성과 탐사선도 후속 계획에 포함합니다.

약 1만 6천 개 규모의 지구 궤도 위성을 표현하는 캠페인도 계획하고 있습니다. **이 항목들은 개발 예정이며 현재 제공되는 기능과 구분합니다.** 구체적인 임무와 구현 방법은 검토 중이며 출시 일정은 정하지 않았습니다.

→ [공개 로드맵](docs/roadmap.md) · [지구 궤도 위성 캠페인 구상](docs/campaigns/earth-orbit.md)

NPC·안드로이드 동료·외계 문명과의 만남, 지속 온라인 우주·연합·평판, 모듈 증축·별도 착륙선 등 기존 기획의 장기 방향은 [만남과 사회의 장기 구상](docs/concepts/future-society.md)에 구분해 두었습니다.

## 이 저장소에 관하여

이곳은 ispacecraft의 공개 소개·사용 안내·로드맵·피드백을 위한 저장소입니다. 애플리케이션 소스 코드는 포함하지 않습니다.

문서 수정 제안과 오탈자 수정은 Pull Request로, 버그 신고와 기능 제안은 [Issues](https://github.com/birdea/ispacecraft-info/issues)로 보내 주세요. [참여 안내](CONTRIBUTING.md)에 필요한 정보를 정리했습니다.

전체 문서는 [문서 목록](docs/README.md)에서 볼 수 있습니다.

[자주 묻는 질문](docs/faq.md) · [데이터와 기기 권한](docs/data-and-permissions.md) · [자료 출처](docs/credits.md)
