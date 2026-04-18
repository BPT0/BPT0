<div align="center">

# 🌱 끊임없이 탐구하는 Android 개발자

> **"좋은 기술은 학습으로, 더 좋은 기술은 검증 후 도입으로."**

새로운 기술이 등장하면 먼저 **학습 → 프로젝트 적합성 검토 → PoC → 실제 도입**의 사이클로 검증합니다.  
단순한 기술 추종이 아닌, **사용자 경험과 코드 품질 개선에 실제로 기여하는지**를 기준으로 판단합니다.

</div>

---

## 🛠 Tech Stack

### Android
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Hilt](https://img.shields.io/badge/Hilt-34A853?style=for-the-badge&logo=google&logoColor=white)
![Room](https://img.shields.io/badge/Room-FF6F00?style=for-the-badge&logo=sqlite&logoColor=white)
![DataStore](https://img.shields.io/badge/DataStore-0F9D58?style=for-the-badge&logo=google&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Flow](https://img.shields.io/badge/Flow-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=for-the-badge&logo=square&logoColor=white)
![OkHttp](https://img.shields.io/badge/OkHttp-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![OneSignal](https://img.shields.io/badge/OneSignal-E54B4D?style=for-the-badge&logo=onesignal&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Kakao SDK](https://img.shields.io/badge/Kakao%20SDK-FEE500?style=for-the-badge&logo=kakao&logoColor=black)

![MVVM](https://img.shields.io/badge/MVVM-4285F4?style=for-the-badge&logo=android&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-00ACC1?style=for-the-badge&logo=android&logoColor=white)

### Environment
![Android Studio](https://img.shields.io/badge/Android%20Studio%20Meerkat-2024.3.1-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![Android SDK](https://img.shields.io/badge/Android%20SDK-Oreo%20(API%2026)-3DDC84?style=for-the-badge&logo=android&logoColor=white)

---

## 📱 Featured Project — 틈틈잇

> **"틈새 시간, 가볍게 쌓이는 학습 루틴"**  
> 하루 중 흘려보내는 짧은 시간을 학습으로 전환하는 마이크로러닝 앱

### 🎯 프로젝트 개요
- **컨셉**: 5~10분 단위의 짧은 학습 세션으로 **틈새 시간 학습 루틴**을 설계
- **타겟**: 바쁜 일상 속에서도 꾸준히 성장하고 싶은 학습자
- **담당**: Android개발자
- **배포**: Google Play Store

### 🏗 아키텍처
- **MVVM + Clean Architecture** (Presentation / Domain / Data 3-Layer)
- **Single Activity + Jetpack Compose** 기반 선언형 UI
- **Hilt** DI로 계층 간 의존성 분리
- **DataStore** 이중화로 구조화 데이터와 설정값을 용도별로 관리
- **Coroutines + Flow** 기반 반응형 비동기 스트림

### ✨ 핵심 기능
- 카카오 및 구글 소셜 로그인 기반 간편 온보딩
- 개인화된 학습 플로우 및 진도 추적
- FCM / OneSignal을 활용한 리마인더 푸시 알림
- Firebase Analytics / Crashlytics로 사용자 행동·안정성 지표 수집

### 🔬 탐구 & 신기술 도입 이력
안드로이드 생태계의 변화에 맞춰, 틈틈잇 프로젝트에 **실제로 적용 가능한지 검증**한 후 점진적으로 도입한 기술들입니다.

| 기술 | 도입 배경 | 검증 결과 |
|------|-----------|-----------|
| **Jetpack Compose** | XML 기반 UI의 보일러플레이트 감소 및 선언형 UI 학습 | 화면 개발 속도 향상, 상태 관리 일관성 확보 |
| **Clean Architecture** | 레이어 간 결합도 감소 및 테스트 용이성 확보 | 비즈니스 로직 독립성 확보, 기능 확장 비용 감소 |
| **DataStore** | SharedPreferences의 동기 I/O 및 타입 안정성 한계 극복 | Coroutines 기반 비동기 처리로 UI 스레드 블로킹 제거 |
| **Kotlin Flow** | LiveData 대비 연산자 풍부도 및 순수성 확보 | UI 상태 스트림 표현력 향상 |

> 🔍 **앞으로 검토 중인 기술**: 현재 적절한 신기술 동향을 보고 있고 지속적으로 검토 중입니다.
위 내용에 대해서는 [Velog 개발 블로그 ](https://velog.io/@kbs95123/posts) 에 게시 중입니다.

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight&hide_border=true)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=tokyo-night&hide_border=true)

</div>
