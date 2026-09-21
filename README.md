# Seung-Hyun-211

유니티 게임 클라이언트 프로그래머입니다. **C#, C++**을 주로 사용하며, **Unity**를 메인 엔진으로 쓰고 **Unreal Engine**도 어느 정도 다룰 수 있습니다.

- 언어: C#, C++
- 엔진: Unity(주력), Unreal Engine
- 그 외: DirectX 11, 멀티스레드 프로그래밍, Go(서버 프로토타입)

---

## 대표 프로젝트

### [usn](https://github.com/Seung-Hyun-211/usn) — 탑다운 2D 멀티플레이어 서바이벌 슈팅 (Unity)
낮/밤 디펜스 루프를 중심으로 한 개인 프로토타입. 캘리버·반동·부착물을 갖춘 총기 시스템, 인벤토리/장비/스킬트리, 입력·트랜스폼·발사체·적 AI를 동기화하는 멀티플레이, Steamworks 연동까지 포함합니다. 기획 문서와 로드맵을 기반으로 시스템을 단계적으로 설계·구현하는 방식으로 진행 중입니다.

### [AI_Lo_Engine_Man_Dul_Gi](https://github.com/Seung-Hyun-211/AI_Lo_Engine_Man_Dul_Gi) — C++20 / DirectX 11 자체 게임 엔진
바닥부터 만든 2D/3D 게임 엔진입니다. 렌더 스레드와 메인 스레드를 분리하고 값 기반 스냅샷으로 경계를 넘기며, JobSystem 기반 병렬 처리, 인스턴스드 렌더링, 셀 셰이딩·그림자·포스트프로세싱(SSAO/안개), FBX 임포트와 애니메이션, 파티클 시스템을 갖추고 있습니다. 이 위에서 웨이브 전투·무기 5종·크라우드를 갖춘 "디펜스 컴뱃" 데모를 구현했습니다. SOLID 원칙을 최우선 설계 기준으로 삼고 있습니다.

### [ClaudeUnityPluginTest](https://github.com/Seung-Hyun-211/ClaudeUnityPluginTest) — Unity 액션 게임 기획/구현
Unity 6(URP) 기반 프로젝트로, 건축 시스템·무기 전투 조작·시점 전환 슈팅·셀 셰이딩 그래픽·상점/퀘스트/인벤토리·부적과 제단 시스템·대화·시네마틱 구조 등 다수의 기획 문서를 바탕으로 게임 시스템을 설계하고 구현하고 있습니다.

### [DppBot](https://github.com/Seung-Hyun-211/DppBot) — 디스코드 음악봇 (C++ 클라이언트 + Go 서버)
C++ 클라이언트(DPP)와 Go 서버를 로컬 HTTP로만 통신하는 2-프로세스 구조로 재설계한 프로젝트입니다. 길드별 동시성 제어, 음성 연결과 오디오 스레드의 생명주기 관리, use-after-free 같은 실제 동시성 버그를 설계 문서로 정리하고 고쳤습니다.

---

## 그 외 프로젝트

**Unity**
- [UnityInputSystem](https://github.com/Seung-Hyun-211/UnityInputSystem) — Unity Input System 기반 PlayerInput 아키텍처. 인터페이스 분리 + 폴링/이벤트 혼용 입력 설계

**Unreal Engine**
- [Unreal_BP](https://github.com/Seung-Hyun-211/Unreal_BP), [Unreal_CPP](https://github.com/Seung-Hyun-211/Unreal_CPP), [cpp_t](https://github.com/Seung-Hyun-211/cpp_t) — 언리얼 엔진 학습/테스트 프로젝트. 코딩 표준, 액터·컨트롤러·컴포넌트, 충돌, Enhanced Input, UMG 등을 정리

---

## 기타 (초기 프로토타입 · 서버 · 학습용)

간단히 언급만 합니다.

- [MyDiscordBot](https://github.com/Seung-Hyun-211/MyDiscordBot), [CPP_Bot](https://github.com/Seung-Hyun-211/CPP_Bot), [Go-Local](https://github.com/Seung-Hyun-211/Go-Local) — DppBot 이전의 초기 디스코드 봇/서버 프로토타입
- [Today-I-Learned](https://github.com/Seung-Hyun-211/Today-I-Learned) — 알고리즘 문제 풀이 및 CS 이론 학습 기록
