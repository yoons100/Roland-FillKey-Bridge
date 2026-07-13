![Platform](https://img.shields.io/badge/platform-Windows-blue) [![Release](https://img.shields.io/badge/Release-V1.2-fc1ba6)](https://github.com/yoons100/Roland-FillKey-Bridge/releases) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/yoons100/Roland-FillKey-Bridge/blob/main/LICENSE)  

## Roland-FillKey-Bridge
Roland FillKey Bridge는 Resolume 등 Spout/NDI를 지원하는 미디어 서버 앱의 RGBA 출력을  
Roland V-1-4K INPUT 5 Fill+Key 형식으로 실시간 변환하는 브리지 프로그램입니다.

### 사용 방법

1. Spout/NDI를 지원하는 미디어 서버 앱(예: Resolume)에서 Spout/NDI Output을 활성화합니다.
2. Roland FillKey Bridge를 실행합니다.
3. 사용할 Spout/NDI Sender를 선택합니다.
4. Output Display를 Roland V-1-4K가 연결된 디스플레이로 선택합니다.
5. Start Output을 클릭하면 Fill+Key 출력이 시작됩니다.
6. Roland 스위처에서 INPUT 5(Fiill&Key)를 선택하여 사용합니다.

### 권장 설정

- Output Resolution : 1920 × 1080 @ 60Hz
- Color Mode : Continuous RGB
- Encode Path : Strict PGM Safe
- Premultiplied Correction : ON

### 시스템 트레이

앱은 시스템 트레이에서 동작합니다.
- On 아이콘 : Spout/NDI 연결됨
- Off 아이콘 : Spout/NDI 연결 안됨

창을 닫아도 프로그램은 종료되지 않고 시스템 트레이에서 계속 실행됩니다.  
완전히 종료하려면 시스템 트레이 아이콘을 우클릭한 후 Exit를 선택하세요.

### 안내

본 프로그램은 Roland Graphics Presenter의 소스코드, 라이브러리 또는 리소스를 사용하지 않은 독립 구현입니다.  
V-1-4K의 공개적으로 관찰 가능한 동작과 자체 제작한 테스트 패턴, 그리고 실험을 통해 확인한 결과를 기반으로 개발되었습니다.

---

## Roland-FillKey-Bridge
Roland FillKey Bridge converts RGBA output from Spout/NDI-compatible media server App (such as Resolume) into a real-time Roland V-series (e.g., V-1-4K) INPUT 5 Fill+Key compatible video stream.

### Quick Start
1. Enable Spout/NDI Output in your Spout/NDI-compatible media server application (e.g. Resolume).
2. Launch Roland FillKey Bridge.
3. Select the desired Spout/NDI Sender.
4. Choose the display connected to the Roland V-1-4K.
5. Click Start Output to begin the encoded Fill+Key output.
6. Select INPUT 5 on the Roland Switcher.

### Recommended Settings
- Output Resolution: 1920 × 1080 @ 60Hz
- Color Mode: Continuous RGB
- Encode Path: Strict PGM Safe
- Premultiplied Correction: ON

### System Tray
The application runs in the Windows system tray.
- On icon – Spout/NDI connected
- Off icon – Spout/NDI disconnected

Closing the main window minimizes the application to the system tray.  
To completely exit the application, right-click the tray icon and choose Exit.

### Notice

This software is an independent implementation and does not contain or use any Roland Graphics Presenter source code, libraries, or resources.  
It has been developed entirely from publicly observable behavior of the Roland V-1-4K, together with custom-built test patterns and extensive independent testing.
