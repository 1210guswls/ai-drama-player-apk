# 밤의 이야기 · Android APK

[최신 APK 다운로드](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk)

현재 **0.4.0 / code 13** · Android 8.0 이상 / arm64-v8a.
기존 앱을 삭제하지 않고 설치하세요. 홈 화면 업데이트 위젯이나 앱 업데이트 버튼으로 받을 수 있습니다.

AI 대화 → 캐릭터 설정집 목록 → 인물별 채팅방 흐름을 제공합니다.
유나·이안과 기존 기록을 보존하고 서연·하린의 오리지널 설정집을 추가했습니다.
목록 진입·새로고침으로 프로필과 공통 프롬프트를 갱신하므로 콘텐츠 변경에는 APK 재설치가 필요하지 않습니다.
기존 방은 프로필/프롬프트 버전을 고정하고 사용자가 ‘새 설정 적용’을 선택해야 변경합니다.

설정집·세계관·방별 기억/상황·최근 역할별 기록·현재 입력을 조립해 기존 OpenRouter로 전달합니다.
모델·키·기억·페르소나·배역은 별도 설정에서 변경합니다. 소설 서재·TTS 캐시·업데이트 위젯은 유지합니다.
AI 대화는 기본 로컬 체험입니다. 실제 OpenRouter 생성에는 본인 키/크레딧과 요청별 비용 확인이 필요합니다.

검증: 단위 테스트 107개, Galaxy S20 Ultra 무음 UI 검사 15개, 실제 Private 설정집 읽기 1개,
알림 도구 검사 17개 통과. lint 오류 0. 메인 앱 업데이트 전후 원래 데이터 104개 파일 해시 동일.
실기기 채팅 화면은 자체 QA 기록/Mock 응답이며 실제 유료 생성 품질·음성·마이크 검사는 하지 않았습니다.
공개 APK 전체 다운로드와 SHA-256을 확인했습니다.

Private 작품·개인 대화·토큰·소스·서명 비밀·알림 채널은 이 저장소에 올리지 않습니다.
GitHub 콘텐츠 읽기 연결과 OpenRouter 생성 키, ChatGPT의 GitHub 연결은 각각 별개입니다.
빌드·필수 검사·공개 다운로드/해시 확인 후 설정된 완료 알림을 한 번 보냅니다.

[update.json](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/update.json) ·
[SHA-256](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk.sha256)

패키지·버전·기존 앱 서명·크기·SHA-256 검증 후 설치합니다. 현재 개인용 전용 QA/debug 서명을 유지합니다.
