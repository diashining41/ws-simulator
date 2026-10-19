# 바이스슈발츠 시뮬레이터 (Weiss Schwarz Simulator)

비공식 팬 제작 바이스슈발츠 시뮬레이터의 **배포용 저장소**입니다. 프로그램 파일은 [Releases](https://github.com/diashining41/ws-simulator/releases)에 있습니다.

AI와 대전하거나, PC·휴대폰끼리 온라인으로 대전하거나, 한 기기에서 둘이 대전하고, 덱을 만들고, 첫 패 확률을 계산할 수 있습니다. 바이스슈발츠·로제·블라우 229개 작품의 공식 카드가 들어 있습니다.

## 내려받기 (최신: 0.7)

| 기기 | 파일 | 필요한 것 |
| --- | --- | --- |
| PC | [WS_Simulator_0.7_PC.zip](https://github.com/diashining41/ws-simulator/releases/download/v0.7/WS_Simulator_0.7_PC.zip) | Windows 10 · 11 (64비트) |
| 모바일 | [WS_Simulator_0.7_Android.zip](https://github.com/diashining41/ws-simulator/releases/download/v0.7/WS_Simulator_0.7_Android.zip) | Android 8.0 이상, ARM64 |
| 모바일 (APK만) | [WSSimulator_0.7.apk](https://github.com/diashining41/ws-simulator/releases/download/v0.7/WSSimulator_0.7.apk) | 위와 같음 |

## 설치

**PC**: 압축을 모두 푼 뒤 `WSSimulator.exe`를 실행합니다. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누릅니다(서명하지 않은 개인 제작 프로그램이라 나오는 안내입니다). 폴더 안의 `CardContent`, `CardContentExtra`는 카드 데이터라서 지우면 안 됩니다.

**안드로이드**: 압축을 풀고 `WSSimulator_0.7.apk`를 눌러 설치합니다. "출처를 알 수 없는 앱" 설치를 허용하고, Play 프로텍트 경고가 나오면 **무시하고 설치**를 누릅니다.

카드 그림은 덱 에디터에서 처음 볼 때 인터넷으로 받아 저장합니다(1장 약 25KB). 내장 AI 덱 20개의 그림은 처음부터 들어 있습니다.

온라인 대전은 두 사람이 같은 판(0.7)이어야 합니다. 이전 판은 [Releases](https://github.com/diashining41/ws-simulator/releases)에 있습니다.

## 피드백

이 프로그램을 받은 게시글에 댓글로 남겨 주세요. 버전, PC/모바일(기종), 어떤 화면에서 무엇을 했을 때 어떻게 됐는지, 가능하면 스크린샷을 함께 적어 주시면 고치기 쉽습니다.

## 안내

- 컴퓨터와 둔 대전의 기록은 AI 개선을 위해 서버로 보내집니다(설정 「컴퓨터 대전 기록을 서버에 보내기」에서 끌 수 있습니다). 온라인 대전 기록도 서버에 보관되어 통계와 AI 개선에 쓰입니다.
- 비공식 팬 제작 시뮬레이터입니다. 바이스슈발츠와 카드 그림·텍스트의 권리는 부시로드와 각 작품의 권리자에게 있습니다.
- PC판은 카드 그림 변환에 [libwebp](https://chromium.googlesource.com/webm/libwebp)(BSD 라이선스)를 씁니다. 라이선스 전문은 PC판 폴더의 `THIRD_PARTY_NOTICES.txt`에 있습니다.
