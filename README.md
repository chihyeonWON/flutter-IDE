# flutter

개발 환경 구축

```
개발 환경 : Android Studio

플러터 SDK 설치
https://docs.flutter.dev/get-started/install/windows

시스템 환경 변수 설정 c:/src/flutter/bin 

환경변수 설정 확인 
C:\Users\ylose>flutter --version
Flutter 3.3.10 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 135454af32 (8 days ago) • 2022-12-15 07:36:55 -0800
Engine • revision 3316dd8728
Tools • Dart 2.18.6 • DevTools 2.15.0
```
## 안드로이드 스튜디오 플러터 플러그인 설치

![image](https://user-images.githubusercontent.com/58906858/209274478-2fd4c1e3-6334-4255-af96-c1cb7fbcca15.png)

## 플러터 프로젝트 생성
![image](https://user-images.githubusercontent.com/58906858/209274849-0ef44d99-84ba-4537-ae11-035f22783937.png)

## 플러터 환경 구성 검사
flutter doctor 명령어로 플러터를 개발할 환경 구성이 잘 되었는지 검사, 가이
![image](https://user-images.githubusercontent.com/58906858/209275164-03a45528-0b2c-4ae2-b13a-24e88b83d128.png)

## 플러터 환경 구성 검사 오류 시

flutter doctor --android-licenses 명령을 실행 하고 모두 y를 입력   
Android sdk를 flutter가 요구하는 수준의 sdk를 다운로드
![image](https://user-images.githubusercontent.com/58906858/209279392-e948af98-b239-4cab-b4d8-83ae43389db5.png)

## 에뮬레이터로 실행 AVD Manager

AVD Manager Pixel 2 기종을 선택하고 R버전을 선택

## 샘플 앱 에뮬레이터로 실행

에뮬레이터가 정상적으로 작동하는 것을 확인할 수 있었습니다.
![image](https://user-images.githubusercontent.com/58906858/209283033-14006d5b-bc20-4dce-abc5-25c4825e3883.png)

