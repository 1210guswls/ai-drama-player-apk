# 밤의 이야기 · Android APK

[최신 APK 다운로드](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk)

현재 **0.2.2 / code 9** · Android 8.0 이상 / arm64-v8a.
기존 앱을 삭제하지 않고 설치하세요. 앱 업데이트 버튼이나 기존 업데이트 위젯으로도 받을 수 있습니다.
Android가 요구하는 설치 승인은 직접 확인해 주세요.

0.2.2: 원문판 듣기 화면에 ‘서연 목소리 · 원문 A/B 비교’를 추가했습니다.
실제 엔진/Voice/언어/속도/피치를 표시하고 같은 문장 3개로 현재/후보를 비교한 뒤 이 배역만 저장합니다.
전역 여성 2번 슬롯, 다른 작품과 배역, 원문과 화자 순서는 유지합니다.
캐릭터별 조정 시 다른 배역의 캐시가 불필요하게 바뀌지 않도록 보완했습니다.

검증: 단위 테스트 92개, 무음 배역 UI 2개, 실제 Private 다운로드/규격/해시 검사 1개 통과.
APK 빌드/lint 오류 0, 인증 없는 전체 APK 다운로드와 SHA-256 일치 확인.
회사 기기에서 소리·TTS 합성·마이크는 실행하지 않았습니다.
서연의 실제 음색 품질과 새 음성 파일 합성/재생은 미검증이며 조용히 들어도 되는 장소에서 A/B 청취 후 확정해야 합니다.
기존 설정/인증/이어 듣기 보존을 확인했습니다.

0.2.x AI 대화는 기본 오프라인 체험이며 정해진 예시 응답입니다.
실제 OpenRouter 생성에는 본인 키/크레딧과 요청별 비용 확인이 필요합니다.
키는 앱에서 직접 입력하고 별도 Keystore에 저장합니다. 자동 유료 요청·자동 재시도는 없습니다.
실제 유료 API·음성 입력/낭독 품질·장시간 배터리/비용 검증은 별도입니다.

이 저장소에는 APK/update.json/해시만 배포합니다. 소스·Private 작품·개인 대화·키·서명키를 업로드하지 않습니다.
앱의 콘텐츠 인증과 ChatGPT GitHub 연결은 별개입니다.

[update.json](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/update.json) ·
[SHA-256](https://github.com/1210guswls/ai-drama-player-apk/releases/latest/download/nightstory-latest.apk.sha256)

전용 앱 서명·패키지·버전·파일 크기·SHA-256을 확인한 뒤 업데이트합니다.
현재는 전용 QA/debug 서명을 유지하는 개인용 배포입니다.