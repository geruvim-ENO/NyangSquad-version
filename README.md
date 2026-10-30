# NyangSquad-version

냥냥방어대(`com.innoversegames.nyangSquad`)의 강제 업데이트 확인용 최신 버전 정보입니다.

- 게임을 켤 때 `version.json`을 읽어, 설치된 앱의 버전 코드가 `latestVersionCode`보다 낮으면 "새 버전이 있어요" 창을 띄우고 스토어로 보냅니다 (업데이트 전에는 플레이 불가).
- 구글 플레이에 새 버전이 배포된 **뒤에** `latestVersionName`, `latestVersionCode`, `updatedAt`을 고칩니다.
- 파일을 못 읽거나 인터넷이 없으면 막지 않고 그대로 플레이합니다.
