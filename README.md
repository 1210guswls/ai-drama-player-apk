# 밤의 이야기 · Android APK

독립 개인용 오디오 드라마 플레이어 배포 저장소입니다. 콘텐츠/게임 저장소와 분리되어 있습니다.

[최신 APK 다운로드](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk)

현재 버전 **0.2.1 / code 8** · Android 8.0 이상 / arm64-v8a.
기존 앱을 삭제하지 않고 업데이트 설치하세요. 앱 설정의 앱 업데이트 또는 기존 업데이트 위젯으로도 받을 수 있습니다.
Android가 요구하면 설치를 승인해 주세요.

0.2.1은 503 / Retry-After: 0에서 HTTP 라이브러리 내부 자동 재요청까지 차단한 패치입니다.

0.2.0: 기존 서재를 유지하고 선택형 AI 대화 탭을 추가했습니다. 키 없이 시작하는 오프라인 체험 캐릭터,
대화방 저장, 다음/이전 장면, 추천 답변과 원본 보존 재생성을 지원합니다.
체험은 정해진 예시이며 실제 AI 응답이 아닙니다.
OpenRouter는 본인 키를 앱 설정에 직접 입력하고 키를 확인한 뒤 요청마다 비용에 동의해야 사용합니다.
자동 유료 요청·자동 재시도·모델/제공자 폴백은 없습니다. 자동 낭독 기본값은 꺼짐입니다.

검증: 단위 테스트 86개, 동일 UI의 0.2.0 S20 무음 UI/저장 검사 7개, lint 오류 0, APK 빌드 및 인증 없는 전체 다운로드/해시 일치.
실제 유료 API·음성 인식/낭독 품질·장시간 배터리/비용은 미검증입니다.
회사 기기에서 소리·마이크 테스트는 하지 않았습니다. 대화 낭독은 전경 기능이며 기존 소설의 백그라운드 재생은 유지합니다.

개인 대화·키·Private 콘텐츠·소스·서명키는 이 저장소에 업로드하지 않습니다.
앱의 콘텐츠 다운로드 인증과 ChatGPT의 GitHub 연결은 별개입니다.

## 업데이트 데이터

[update.json](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/update.json) ·
[SHA-256](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk.sha256)

전용 앱 서명으로 패키지·버전·크기·SHA-256·기존 설치 서명을 확인한 뒤 업데이트합니다.
현재는 독립 QA/debug 서명을 유지한 개인용 배포입니다.