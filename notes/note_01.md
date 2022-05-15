# 리눅스 기초

## cli
---
- command line interface
## cli 명령어
---
###  현재 디렉토리 내 내용 리스팅
```linux
ls

ls -al
ls -l
ls -a
```
### 현재 디랙토리 위치 확인
```linux
pwd
```
### 디렉토리 생성
```linux
mkdir
```
### 파일 생성
```linux
touch
```
### 디렉토리 이동
```linux
cd

cd / 
cd [디렉토리명]
cd ~
```
### 현 화면 정리
```linux
clear
```
### 파일, 디렉토리 삭제
```linux
rm [파일명]

rm -r [디렉토리명]
```
### 도움말
```linux
[명령어] ---help
```
명령어에 대한 도뭄말
```linux
man [명령어]
```
명령어에 대한 메뉴얼
```linux
man [명령어]

메뉴얼이 열린 상태
/ [검색어]
n
```
검색후 n을 이용해서 검색결과사이로 이동
### 복사
```linux
cp [복사할 파일] [복사할 경로]
```
### 이동
```linux
mv [이동할 파일] [이동할 경로]
```
### 이름바꾸기
```linux
mv [이름바꿀 파일] [바뀔이름]
```
mv 명령어를 이동, 리네임 으로 사용
### 파일의 내용을 터미널 상에 출력
```linux
cat [파일명]
```