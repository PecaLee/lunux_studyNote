# 리눅스 기초

## 패키지 매니져
---
기본적으로 가지고 있지 않은 어플리케이션(프로그램)을 설치.
- apt
- yum   
- homebrew(맥의 경우)
등등
## apt
---
### 패키지 매니져의 소프트웨어 목록 업데이트
```linux
sudo apt-get update
```
### 패키지 매니져 내 검색
```linux
sudo apt-cache search [검색어]
```
### 설치
```linux
sudo apt-get install [프로그램 명]
```
### 업데이트
```linux
sudo apt-get upgrade
sudo apt-get upgrade [프로그램 명]
```
### 삭제
```linux
sudo apt-get remove [프로그램 명]
```
