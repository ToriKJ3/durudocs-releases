# 두루문서 (DuruDocs)

HWP · HWPX · DOCX · DOC · RTF · Markdown · HTML · TXT 를 열고, 고치고, 저장하는 데스크톱 문서 편집기입니다.
이 저장소는 설치 파일 배포와 자동 업데이트 전용입니다.

## 내려받기

[최신 버전 받기](https://github.com/ToriKJ3/durudocs-releases/releases/latest)

| 운영체제 | 파일 |
|---|---|
| Windows | `DuruDocs-버전-win-x64-setup.exe` |
| macOS (Apple 실리콘: M1 이후) | `DuruDocs-버전-mac-arm64.dmg` |
| macOS (Intel) | `DuruDocs-버전-mac-x64.dmg` |

한 번 설치하면 다음 버전부터는 앱이 스스로 내려받아 설치합니다. 앱을 끌 때 또는 '다시 시작'을 누를 때 적용됩니다.

## macOS 에서 처음 열 때

Apple 개발자 인증서로 서명되지 않은 앱이라 "손상되었습니다" 경고가 나올 수 있습니다.
응용 프로그램 폴더로 옮긴 뒤 터미널에서 아래 명령을 한 번 실행해 주세요.

```bash
xattr -cr /Applications/DuruDocs.app
```

자동 업데이트를 쓰려면 앱이 응용 프로그램 폴더에 있어야 합니다.

## Windows 에서 처음 열 때

코드 서명이 없어 SmartScreen 경고가 나올 수 있습니다. '추가 정보' → '실행'을 눌러 주세요.
