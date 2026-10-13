## mountainn

Flutter로 모바일 앱을 만들어요. 네이티브가 필요하면 Kotlin까지 내려갑니다.
기능을 하나 더 내는 것보다 서비스가 안정적으로 돌아가는 걸 기준으로 기술을 고르고 구조를 짭니다.

- LightWeight에서 운동 머신과 Supabase Realtime으로 연동되는 회원 앱과 트레이너 앱(Android · iOS)을 혼자 맡아 만들어요.
- 문자 인증이 자꾸 안 와서 국내 SMS 업체를 비교하고 NHN Cloud + 서버 OTP 방식으로 옮겼어요. 국내 도달률 100%, 일본 사용자 98.9%가 받아요.
- 모든 ViewModel이 API 호출·비즈니스 로직·화면 상태를 다 맡고 있던 레거시를 책임별로 다시 나눴어요. 반복되던 상태 버그가 사라졌고, 경계는 검사 스크립트와 CI가 대신 지켜요.
- 크래시가 나면 사내 메신저로 바로 알림이 오고 GitHub 이슈로 자동 등록되게 Crashlytics를 연동했어요. 장애 대응은 감지 속도가 반이에요.
- 팀 코딩 규칙은 Claude Code 스킬로 직접 써 뒀어요. 사람이든 AI 에이전트든 같은 기준으로 코드를 짜고 리뷰해요.
- 요즘은 트레이너용 태블릿 앱을 새로 만들고 있어요.
- 삽질한 건 [블로그](https://mountaincoding.tistory.com/)에 적어 둡니다.

<img src="https://skillicons.dev/icons?i=dart,flutter,kotlin,androidstudio,firebase,supabase,sqlite,git,figma" alt="Dart, Flutter, Kotlin, Android Studio, Firebase, Supabase, SQLite, Git, Figma" />
