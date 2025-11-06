![header](https://capsule-render.vercel.app/api?type=rect&color=1E1E1E&height=180&section=header&text=RED%20HOOD&fontSize=90&&fontColor=D32F2F&fontAlign=70)
![5](https://github.com/user-attachments/assets/daa48c1d-6ebd-4163-a6cf-d45dc895affe)


## 프로젝트 소개
> **이런, RedHood가 게임 세상에 빠져버렸습니다!  
RedHood가 무사히 탈출할 수 있게 도와주세요!**

${\textsf{\color{red}RED HOOD}}$는 **2D 플랫포머 로그라이크** 게임입니다.

다양한 아이템을 획득하고 시너지를 활성화해 적들을 물리치세요.

각성 상태를 활성화하고 더 강력한 공격을 퍼붓는 손맛도 놓치지 마세요!
</br>
</br>

> 장르: 2D 플랫포머 로그라이크  
> 개발 기간: 2025.09.02 ~ 2025.11.07  
> 플랫폼: PC
</br>

### 프로젝트 개요 및 목표
${\textsf{\color{red}RED HOOD}}$는 **로그라이크** 게임으로 같은 던전을 반복 진행하여 목표를 달성하는 게임입니다. 
때문에 플레이어가 같은 구간을 반복 진행 하더라도 지루한 경험의 폭을 줄이는 것이 목표입니다.

> 반복 진행으로 겪는 부담감 완화
1. 속도감 있는 게임
    - 2단 점프는 적과의 거리를 빠르게 줄일 수 있으며, 대부분의 상황에서 사용 가능한 대쉬는 플레이어의 움직임을 제한하는 상황을 완화합니다.
2. 랜덤 등장 요소
    - 랜덤으로 등장하는 아이템과 던전의 구성 때문에 플레이어는 매번 다른 상황을 마주하게 됩니다. 이를 통해 플레이어가 반복 진행으로 겪는 부담감을 완화 시켰습니다.
3. 차별화
    - 플레이어와 운과 선택은 게임의 경험을 변화 시킵니다. 저희는 플레이어의 선택을 존중하여 일정 시간동안 성장치를 극대화 시키는 각성 상태를 제공했습니다.
    - 랜덤 등장 요소는 플레이어의 반복 진행을 흥미롭게 만들지만, 플레이어가 게임 진행을 제어할 수 없다는 단점이 있습니다. 때문에 일부의 선택지를 제공하고, 시너지 효과를 추가해 플레이어가 운의 요소에서 일부 선택할 수 있게 되었습니다. 플레이어는 자신의 운에 맞는 전략을 세워야 합니다.

### 플레이 영상 및 스크린샷
[![Video Label](http://img.youtube.com/vi/yOj1v_jEO9o/0.jpg)](https://youtu.be/yOj1v_jEO9o)  

아이템
이미지링크 | 이미지링크 |
---|---|

---
## 팀 소개
|이름|역할|블로그|깃허브|연락처|담당|
|------|---|---|---|---|---|
|고승진|기획자, PM|-|-|rokid_@naver.com|플레이어, 스킬, 아이템, 시너지|
|김기태|기획자|-|-|-|몬스터, 스테이지|
|김예찬|개발자, PM|-|-|-|아이템|
|김남진|개발자|[블로그](https://velog.io/@jinnam/posts)|[깃허브](https://github.com/UserJin)|skawls1126@gmail.com|몬스터, 스테이지, 애널리틱스|
|최우영|개발자|[블로그](https://www.notion.so/20dea92ed40680fdaeb1c85971f6b614)|[깃허브](https://github.com/wooyoung-1)|wooyoung7749@gmail.com|플레이어, UI, 연출, 폴리싱|
---
## 주요 기능
---
## 기술적인 도전 과제
- Behavior Tree를 통한 보스 몬스터 AI 구조 설계
- 몬스터의 플레이어 탐색 방식 최적화
- 세분화된 몬스터 클래스 통합 및 전략 패턴 적용
  
- GSTU를 사용하여 실시간 데이터 로드
- 아이템 이미지 Web Request를 통해 실시간 로드
- AudioManager를 통한 오디오 관리 구조 설계

- FSM을 이용한 플레이어, UI 상태 구조 설계
- 프리펩 기반의 동적 맵 관리
- 동적 연출 이벤트 관리
---
## 기술 스택
### Data
- Addressable
- Scriptable Object
- NewtonsoftJson
- PlayerPrefs

### DesignPattern
- Singleton
- Observer
- Behaviour Tree
- Finite-State Machine

### Obtimization
- ObjectPooling
- Awaitable
- WebRequest(GET)

### Infra
- GSTU
- C# Extension
- Unity Analytics

### Tool Asset
- Dotween Pro
- Text Animation Pro

### AI
- Claude Code
- Gemini-CLI
- NanoBanana
- ChatGPT
- MCP
    - Gemini
    - Serena

---
## 조작법
| 동작             | 키보드 입력     |
|------------------|-----------------|
| 이동             | 방향키          |
| 점프             | Space           |
| 공격             | A   |
| 대쉬             | S          |
| 각성             | D   |
| 스킬 1             | Q   |
| 스킬 2             | W   |
| 상호작용         | F               |
| 메뉴 열기        | ESC             |

---
## 링크
[브로셔](https://www.notion.so/teamsparta/10-RedHood-2992dc3ef514803b8ac3d726e13bc1ac)

[유저 테스트 결과보고서](https://www.notion.so/2a0a69a8b2d0800ea598fd5602ad098a?source=copy_link)
