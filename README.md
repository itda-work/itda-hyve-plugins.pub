# itda-hyve 플러그인 배포

[itda-hyve](https://github.com/itda-work/itda-hyve.pub) 용 플러그인의 **설치 파일만** 올리는 곳입니다. 소스 코드는 공개하지 않습니다.

## 설치

여기서 파일을 직접 받을 필요는 없습니다. itda-hyve 의 **설정 › 서비스 › 플러그인 › 추가**에서 플러그인을 고르거나, 안내받은 manifest 주소(`…/manifest.json`)를 붙여 넣으면 itda-hyve 가 받아서 확인한 뒤 설치합니다.

- 설치 파일은 암호화돼 있어 itda-hyve 로만 설치할 수 있습니다.
- itda-hyve 는 받은 파일의 SHA-256 과 실행 파일 해시를 manifest 와 대조하고, 플러그인을 시험으로 띄워 확인한 다음, 사용자가 권한 화면에서 확인해야 설치를 끝냅니다.
- macOS 에서는 itda-work 게시자 키로 서명된 플러그인만 실행됩니다.

## Release 이름

`<플러그인>/v<판>` (예: `mykakao/v0.3.1`). 한 번 올린 판의 파일은 바꾸지 않습니다 — 고칠 것이 있으면 판을 올려 새로 냅니다.

문의: itda-work
