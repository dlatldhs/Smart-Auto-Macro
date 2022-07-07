# Smart-Auto-Macro
자가진단을 자동으로 해주는 프로그램

## 개발 목적
##### 컴퓨터로도 빠르게 자가 진단을 하기 위해서 
## 만들게 된 이유 / 동기
##### 학교에서 자가진단을 하는 것을 잊어 버리고 휴대폰을 낼 때 자가진단을 노트북으로 해야하는데 노트북으로 하면 웹에 들어가서 로그인 하고 학교 정보 같은 것들을 전부 입력해야해서 매우 귀찮고 시간이 오래 걸린다. 그래서 이 프로그램을 개발하여 만약에 자가진단을 하지 않은 채 휴대폰을 제출해도 빠르게 실행하여 시간을 절약 할 수 있고 귀찮음도 덜어낼 수 있다.

## 사용 프로그램
chromedriver.exe( 자신이 사용중인 chrome 버전에 맞게 설치해야됨 )<br>[설치하는 곳](https://chromedriver.chromium.org/downloads) 

## 사용한 라이브러리
```
selenium
time
pyautogui
lib2to3.pgen2 import driver
webdirver_manager
```
## 기술 스택
![image](https://user-images.githubusercontent.com/80656700/177704358-f1f642e7-3af4-4361-a8c6-0e9775c88e29.png)

### 주의점
##### chromedirver가 지금 현재 사용하고 있는( 사용자가 사용하고 있는 것과 버전이 다르다면 실행이 되지 않는다. )<br>자가진단 사이트 자체가 막아놓을려고 그런진 모르겠지만 update를 많이해서 자주 바뀐다. -> 양식이 바껴서 잘 안됨 

## 실행화면 
![image](https://user-images.githubusercontent.com/80656700/177703893-eafcecf9-a7f6-4e21-9322-8fe5c99cbe34.png)
