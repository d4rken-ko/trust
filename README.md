Trust - 이벤트 로거
==============

[Google Play](https://play.google.com/store/apps/details?id=eu.thedarken.trust)에서 이용 가능

Android용 소형 이벤트 로깅 도구입니다.

Trust는 사용자를 위해 소형 이벤트 로그를 보관합니다.

앱 변경, 휴대전화를 사용하는 사람, 놓친 전화 등 Trust가 무슨 일이 언제 일어났는지 알려줍니다.

현재 이벤트에는 다음이 포함됩니다.
- 실행된 앱(Android 5.0에서는 사용할 수 없음)
- 설치/삭제/교체/재시작/지운 앱
- 전원 연결/연결 해제
- 종료/부팅
- 화면 켜기/끄기 이벤트
- 잠금 화면 이벤트
- wifi/셀 연결 끊김
- 미디어 제거
- 통화

Trust에 **PERMISSION**이 필요한 이유는 무엇입니까?
* 수신 또는 발신 통화를 감지하려면 PROCESS_OUTGOING_CALLS가 필요합니다.
* 자동 시작 및 재부팅 감지를 위해 RECEIVE_BOOT_COMPLETED가 필요합니다.
* 연결 변경을 감지하려면 READ_PHONE_STATE가 필요합니다.
* 데이터베이스를 내보내려면 WRITE_EXTERNAL_STORAGE가 필요합니다.
* 현재 포그라운드 앱에 대한 GET_TASKS가 필요합니다.
* wifi SSID에 대한 ACCESS_WIFI_STATE가 필요합니다.
