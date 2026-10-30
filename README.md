# 바이스슈발츠 시뮬레이터 (Weiss Schwarz Simulator)

비공식 팬 제작 바이스슈발츠 시뮬레이터의 **배포용 저장소**입니다. 프로그램 파일은 [Releases](https://github.com/diashining41/ws-simulator/releases)에 있습니다.

AI와 대전하거나, PC·휴대폰끼리 온라인으로 대전하거나, 한 기기에서 둘이 대전하고, 덱을 만들고, 첫 패 확률을 계산할 수 있습니다. 바이스슈발츠·로제·블라우 229개 작품의 공식 카드가 들어 있습니다.

## 내려받기 (최신: 0.10)

| 기기 | 파일 | 필요한 것 |
| --- | --- | --- |
| PC | [WS_Simulator_0.10_PC.zip](https://github.com/diashining41/ws-simulator/releases/download/v0.10/WS_Simulator_0.10_PC.zip) | Windows 10 · 11 (64비트) |
| 모바일 | [WS_Simulator_0.10_Android.zip](https://github.com/diashining41/ws-simulator/releases/download/v0.10/WS_Simulator_0.10_Android.zip) | Android 8.0 이상, ARM64 |
| 모바일 (APK만) | [WSSimulator_0.10.apk](https://github.com/diashining41/ws-simulator/releases/download/v0.10/WSSimulator_0.10.apk) | 위와 같음 |

0.8부터 앱이 새 카드 데이터와 새 버전을 스스로 받습니다(자동 업데이트). 0.8 이상을 쓰고 있다면 앱을 켜기만 하면 0.10을 받습니다. 0.7 이전 판을 쓰고 있거나 자동 업데이트가 되지 않으면 0.10을 한 번만 직접 받아 설치하면 됩니다.

## 설치

**PC**: 바탕 화면이나 문서 같은 내 폴더에 압축을 모두 푼 뒤 `WSSimulator.exe`를 실행합니다. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누릅니다(서명하지 않은 개인 제작 프로그램이라 나오는 안내입니다). 폴더 안의 `CardContent`, `CardContentExtra`는 카드 데이터, `WSUpdater.exe`는 업데이트 프로그램이라서 지우면 안 됩니다. `C:\Program Files`처럼 파일을 쓸 수 없는 곳에 풀면 자동 업데이트를 적용하지 못합니다.

**안드로이드**: `WSSimulator_0.10.apk`를 눌러 설치합니다(압축본은 먼저 압축을 풉니다). "출처를 알 수 없는 앱" 설치를 허용하고, Play 프로텍트 경고가 나오면 **무시하고 설치**를 누릅니다. 새 버전이 나오면 앱이 받아 두고 「설치」를 물어봅니다. 갤럭시 휴대폰은 「보안 위험 자동 차단」이 켜져 있으면 설치되지 않으니 **설정 → 보안 및 개인정보 보호 → 보안 위험 자동 차단**을 끈 뒤 설치하세요(설치가 끝나면 다시 켜도 됩니다).

카드 그림은 덱 에디터에서 처음 볼 때 인터넷으로 받아 저장합니다(1장 약 25KB). 내장 AI 덱 20개의 그림은 처음부터 들어 있습니다.

온라인 대전은 두 사람이 같은 판(0.10)이어야 합니다. 이전 판은 [Releases](https://github.com/diashining41/ws-simulator/releases)에 있습니다.

## 피드백

이 프로그램을 받은 게시글에 댓글로 남겨 주세요. 버전, PC/모바일(기종), 어떤 화면에서 무엇을 했을 때 어떻게 됐는지, 가능하면 스크린샷을 함께 적어 주시면 고치기 쉽습니다.

## 안내

- 비공식 팬 제작 시뮬레이터입니다. 바이스슈발츠와 카드 그림·텍스트의 권리는 부시로드와 각 작품의 권리자에게 있습니다.
- PC판은 카드 그림 변환에 [libwebp](https://chromium.googlesource.com/webm/libwebp)(BSD 라이선스)를 씁니다. 라이선스 전문은 PC판 폴더의 `THIRD_PARTY_NOTICES.txt`에 있습니다.
