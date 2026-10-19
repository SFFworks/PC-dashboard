# PC Dashboard

**Turn your Toss Front or Terminal into a companion dashboard for your Windows PC.**

토스 프론트·터미널을 Windows PC용 대시보드로 활용하는 프로젝트입니다.

PC 상태 확인, 음악 재생, 오디오 제어, 앱 실행을 한 화면에서 사용할 수 있습니다. 호환 터미널에서는 음악·PC 상태 티켓도 출력할 수 있습니다.

> **Test release / 테스트 배포**
>
> Android **0.9.25** · Windows **0.9.6**
>
> 사용해 보시고 오류나 개선 의견을 Issues에 남겨주세요.

## Download / 다운로드

### [→ Releases에서 다운로드 / Download from Releases](https://github.com/SFFworks/PC-dashboard/releases)

| File | 용도 / Purpose |
|---|---|
| `PcDashboard-0.9.25.apk` | Android 대시보드 앱 / Android dashboard |
| `PcDashboard-PC-0.9.6.zip` | Windows PC 프로그램·설치 안내 / Windows companion app and instructions |

**Windows ZIP은 전체를 압축 해제한 뒤 `Setup.exe`를 실행하세요.**

Extract the entire Windows ZIP before running `Setup.exe`.

## Features / 주요 기능

- **PC monitoring** — CPU/GPU usage and temperatures  
  CPU·GPU 사용률 및 온도 확인

- **Music controls** — Album artwork, track information, playback and seeking  
  앨범 커버·곡 정보·재생 제어·재생 위치 변경

- **Audio controls** — Output switching, volume, speaker and microphone mute  
  출력 장치 전환·음량 조절·스피커 및 마이크 음소거

- **App volume** — Separate master and supported application volume controls  
  전체 음량과 지원 앱의 음량을 따로 조절

- **App shortcuts** — Configurable application launch buttons  
  원하는 PC 프로그램을 실행하는 바로가기

- **Appearance** — Themes, album-based colors, Clean and Control Center layouts  
  테마·앨범 색상 연동·클린 및 제어센터 디자인

- **Device modes** — Front and Terminal layouts  
  프론트·터미널 모드 및 터미널의 총 6개·8개 버튼 배치

- **Ticket printing** — Music and PC status tickets on compatible terminals  
  호환 터미널의 음악·PC 상태 티켓 출력

- **PC companion** — System tray operation and optional elevated startup  
  트레이 실행·선택 가능한 관리자 권한 자동 실행

## Tested devices / 작동 확인 기기

| Device | Status |
|---|---|
| Toss Front, 2nd generation / 토스 프론트 2세대 | Tested / 작동 확인 |
| Toss Terminal, 1st generation / 토스 터미널 1세대 | Tested / 작동 확인 |

Other Android devices have not been fully verified. Printer support depends on compatible hardware and a separate printer service.

다른 Android 기기는 충분히 검증하지 않았습니다. 인쇄 기능은 호환 프린터와 별도의 프린터 서비스가 필요하며, 해당 서비스 앱은 이 배포에 포함하지 않습니다.

## Setup / 설치 및 연결

### 한국어

1. Windows ZIP을 전체 압축 해제하고 `Setup.exe`로 PC 프로그램을 설치합니다.
2. Android 기기에 APK를 설치합니다.
3. PC와 Android 기기를 같은 LAN/Wi-Fi에 연결합니다.
4. Android의 **설정 → PC 연결**에서 PC를 검색하고, PC 프로그램에 표시된 API 토큰으로 연결합니다.
5. PC 프로그램의 **오디오**에서 스피커·이어폰 장치를 지정하고 저장합니다.
6. **앱 버튼**에서 실행할 프로그램의 위치와 필요한 실행 인수를 설정합니다.
7. Android의 **설정 → 기기 모드**에서 프론트 또는 터미널을 선택합니다.

CPU 온도 등 일부 센서에는 관리자 권한과 호환 드라이버가 필요할 수 있습니다. 필요한 경우 PC 프로그램의 시스템 준비·진단 안내를 확인하세요.

### English

1. Extract the complete Windows ZIP and install the companion app using `Setup.exe`.
2. Install the APK on your Android device.
3. Connect both devices to the same LAN/Wi-Fi network.
4. Open **Settings → PC connection** on Android, discover your PC, and pair using the API token shown in the PC app.
5. Configure your speaker and headphone devices in the PC app.
6. Set executable paths and any required launch arguments for app shortcuts.
7. Select Front or Terminal under **Settings → Device mode** on Android.

Some sensors, including CPU temperatures, may require administrator privileges and compatible drivers. Check the PC app's preparation and diagnostic tools when needed.

## Feedback / 피드백

### [→ Report an issue / 오류·개선 의견 남기기](https://github.com/SFFworks/PC-dashboard/issues)

Please include / 아래 내용을 함께 알려주세요:

- Device model / 기기 모델
- Android and Windows versions / Android·Windows 버전
- Dashboard app versions / 대시보드 앱 버전
- Steps to reproduce / 문제가 발생하는 순서
- Screenshots, if helpful / 필요한 경우 스크린샷

**Do not include API tokens or private settings in reports.**

**API 토큰이나 개인 설정이 보이는 화면·파일은 올리지 말아주세요.**

## Project information / 프로젝트 안내

This repository currently provides downloads, documentation, and issue tracking. Project source code is not currently published here.

현재 이 저장소는 설치 파일 배포·사용 안내·피드백 접수용이며, 프로젝트 소스코드는 공개하지 않습니다.

Third-party libraries and icons remain subject to their respective licenses. See the notices included with the downloads.

외부 라이브러리와 아이콘에는 각각의 라이선스가 적용됩니다. 배포 파일에 포함된 고지를 확인해 주세요.

This is an independent community project, not an official Toss product.

이 프로젝트는 개인이 제작한 커뮤니티 프로젝트이며 토스의 공식 제품이 아닙니다.
