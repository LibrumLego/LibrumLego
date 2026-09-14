![Jimin Kook — Product-minded Software Developer](portfolio-banner.svg)

<div align="center">
  <sub>PRODUCT-MINDED SOFTWARE DEVELOPER</sub>
  <h2>데이터와 상태를 정리해, 끝까지 동작하는 제품을 만듭니다.</h2>
  <p>
    Kotlin·Android와 React·TypeScript를 중심으로<br/>
    AI, 외부 API, 센서 데이터를 실제 사용자 흐름에 연결합니다.
  </p>
  <p>
    <a href="https://github.com/LibrumLego/Toma"><strong>TOMA</strong></a>
    &nbsp;·&nbsp;
    <a href="https://github.com/LibrumLego/tremor-station"><strong>Tremor Station</strong></a>
    &nbsp;·&nbsp;
    <a href="https://librumlego.github.io/bullet-reclaimer/"><strong>Playable Project</strong></a>
  </p>
</div>

---

## What I bring

| 데이터 구조 | 안정적인 상태 흐름 | 완성하고 배포하는 힘 |
| :--- | :--- | :--- |
| 서로 다른 입력을 공통 모델로 정리해 화면·저장·후속 기능에서 재사용합니다. | 로딩, 실패, 권한, 늦은 응답과 실행 환경 차이를 정상 흐름과 함께 설계합니다. | 팀 기능 통합부터 플랫폼 검증, 문서화와 배포까지 결과물로 마무리합니다. |

<div align="center">
  <kbd>4인 팀장</kbd>&nbsp;&nbsp;
  <kbd>8개 공통 데이터 필드</kbd>&nbsp;&nbsp;
  <kbd>캡스톤 A0</kbd>&nbsp;&nbsp;
  <kbd>앱인토스 출시</kbd>&nbsp;&nbsp;
  <kbd>GitHub Pages 자동 배포</kbd>
</div>

## Featured projects

<table>
  <tr>
    <td width="24%">
      <sub>ANDROID · TEAM PROJECT</sub><br/>
      <h3><a href="https://github.com/LibrumLego/Toma">TOMA</a></h3>
      <code>Kotlin</code> <code>Compose</code> <code>Room</code>
    </td>
    <td>
      <strong>여러 형태의 입력을 하나의 레시피 데이터 계약으로 통합한 AI 주방 도우미</strong><br/><br/>
      4인 팀장으로 아키텍처와 데이터 흐름을 맡았습니다. 텍스트·웹·블로그·유튜브·이미지 분석 결과를 8개 핵심 필드로 정규화해 상세 화면, Room 저장, 음성 안내와 추천 타이머에서 같은 구조를 사용하도록 연결했습니다.<br/><br/>
      <sub>RESULT · 팀 기능 통합 · 캡스톤디자인 A0</sub>
    </td>
  </tr>
  <tr>
    <td>
      <sub>WEB · RELEASED PRODUCT</sub><br/>
      <h3><a href="https://github.com/LibrumLego/tremor-station">Tremor Station</a></h3>
      <code>React</code> <code>TypeScript</code> <code>Vite</code>
    </td>
    <td>
      <strong>센서 입력을 측정·해석·기록 흐름으로 만든 앱인토스 미니앱</strong><br/><br/>
      센서 권한, 실시간 파형, 결과 저장을 상태로 분리했습니다. 센서 이벤트 부재와 백그라운드 전환에 대응해 멈춘 화면이나 잘못된 기록이 남지 않도록 처리하고 실제 플랫폼 출시까지 완료했습니다.<br/><br/>
      <sub>RESULT · 개인 기획·개발·검증 · 앱인토스 출시</sub>
    </td>
  </tr>
  <tr>
    <td>
      <sub>GAME · PLAYABLE BUILD</sub><br/>
      <h3><a href="https://github.com/LibrumLego/bullet-reclaimer">Bullet Reclaimer</a></h3>
      <code>Phaser 3</code> <code>TypeScript</code> <code>CI/CD</code>
    </td>
    <td>
      <strong>시간을 멈추고 단 한 발의 도탄 경로를 설계하는 웹 액션 게임</strong><br/><br/>
      충돌과 반사 계산을 화면 코드에서 분리하고, 모서리 충돌과 연속 반사 같은 경계 조건을 검증했습니다. GitHub Actions로 빌드와 Pages 배포를 자동화해 바로 플레이할 수 있는 결과물로 공개했습니다.<br/><br/>
      <a href="https://librumlego.github.io/bullet-reclaimer/"><strong>Play live ↗</strong></a>
    </td>
  </tr>
</table>

## Engineering focus

```text
Input / Event
      ↓
Normalize data ──→ Model state ──→ UI & storage
      ↓                  ↓
Validate failure     Verify on target environment
```

- **Data contracts** — 입력 방식이 달라도 후속 기능은 같은 모델을 사용하도록 구조를 먼저 정합니다.
- **Failure-aware UX** — 성공 화면뿐 아니라 빈 결과, 권한 거부, API 실패와 재시도 흐름을 구현합니다.
- **Evidence over claims** — README, 실행 방법, 테스트 기준, 데모와 배포 결과로 작업 범위를 확인할 수 있게 합니다.

## Technology

| Area | Stack |
| :--- | :--- |
| Android | Kotlin · Jetpack Compose · ViewModel · Room |
| Web | TypeScript · React · Next.js · Vite · Canvas |
| Integration | REST API · OpenAI API · Firebase · AWS Lambda · Apps in Toss |
| Workflow | Git · GitHub Actions · Vercel · GitHub Pages |

<details>
<summary><strong>Additional work</strong></summary>

| Project | What it demonstrates |
| :--- | :--- |
| [AI News Insight](https://github.com/LibrumLego/ai-news-summarizer) | 외부 API 응답 형식 정규화, 로딩·중복 요청·실패 상태 처리 |
| [Clicker](https://github.com/LibrumLego/Clicker) | Android 상태 관리, 사용자 설정 저장, 배포 흐름 고려 |
| [일단보류 · Hold First](https://github.com/LibrumLego/hold-first) | 소비 기록·숙려·재결정으로 이어지는 행동 흐름 설계 |
| [원곡 보더리스](https://github.com/LibrumLego/wongok-borderless) | 다국어 관광 정보, 지도 검색, AI 추천과 도보 코스 연결 |

</details>

<details>
<summary><strong>Experiments & competitions</strong></summary>

- **NAN 2026 Game × AI Hackathon** — Bullet Reclaimer 제작 및 제출
- **NYPC Master Qualification Round** — 패배 로그 9판 분석, 전략 봇 버전 간 반복 대전과 회귀 검증
- **2026 관광데이터 활용 공모전** — 원곡 보더리스 개발 진행

</details>

---

<div align="center">
  <sub>JIMIN KOOK · ANDROID / WEB / AI-INTEGRATED PRODUCTS</sub>
</div>
