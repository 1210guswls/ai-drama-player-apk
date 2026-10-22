# 밤의 이야기 · Android APK

[최신 APK 다운로드](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk)

현재 **0.5.0 / code 14** · Android 8.0 이상 / arm64-v8a.
기존 앱을 삭제하지 않고 설치하세요. 홈 화면 업데이트 위젯이나 앱 업데이트 버튼으로도 받을 수 있습니다.

AI 대화는 캐릭터 설정집 목록 → 캐릭터별 메신저 채팅방 흐름입니다.
기존 유나·이안·서연·하린을 보존하고 비공식 팬 캐릭터 지우와 공통 프롬프트 v2를 연결했습니다.
전체 설정집 대신 runtime_card·관련 지식·확정 기억·최근 대화를 조립하고 입력마다 답변 하나를 요청합니다.
월 비용 한도, 실제 사용량과 캐시 통계, 캐릭터별 음성과 대사만 읽는 TTS 큐를 지원합니다.
기존 방은 설정집/프롬프트 버전을 고정하며 ‘새 설정 적용’을 명시적으로 선택해야 바뀝니다.

소설 서재·API 키·대화·기억·TTS 캐시·업데이트 위젯은 유지합니다.
AI 대화는 기본 로컬 체험입니다. 실제 OpenRouter 응답에는 본인 키/크레딧과 요청별 비용 확인이 필요합니다.
캐시 적중이나 할인은 보장하지 않으며 비용 미제공 요청은 예약액을 유지합니다.

검증: 단위 테스트 128개, Galaxy S20 Ultra 무음 UI/저장 검사 17개, 실제 Private 저장소 읽기 1개,
알림 도구 검사 17개 통과. lint 오류 0. 원본 보호 데이터 104개 파일의 업데이트 전후 해시가 같습니다.
실기기 대화는 자체 QA/Mock 응답입니다. 실제 유료 모델 품질·과금 절감률·캐시 적중률과 음성 청취·마이크는 미검증입니다.
공개 APK의 전체 익명 다운로드와 SHA-256 검증 후에만 배포 완료 알림을 보냅니다.

Private 작품·개인 대화·토큰·소스·서명 비밀·알림 채널은 이 저장소에 올리지 않습니다.
GitHub 읽기 권한, OpenRouter 개인 키, ChatGPT의 GitHub 연결은 별개입니다.

[update.json](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/update.json) ·
[SHA-256](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk.sha256)

패키지·서명·버전·허용 링크·크기·SHA-256 검증 후 설치합니다. 같은 서명의 전용 QA/debug 빌드를 사용합니다.

## 주요 화면

[서재·재생·보관함·설정·캐릭터 목록·메신저 스크린샷 6장 보기](screenshots/0.5.0/README.md)

실기기에서 개인 계정 없는 QA 앱으로 캡처했습니다. 대화는 로컬 Mock 예시입니다.
