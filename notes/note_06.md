# IO Redirection
 - input, output redirection

## Standard Output
---
### 출력의 방향을 바꿀 수 있다.
### 출력의 결과값을 어떠한 파일에 저장할 수도 있다.
```linux
ls -l > list.txt
```

### 디렉토리 검색 결과를 `list.txt`에 저장
 ```linux
 [명령어] 1> [result.txt]

 [명령어] 2> [error.log]
 ```
 - `1>, >` 스텐다드 아웃풋
 - `2>` 스탠다드 에러

## Standard Inpug
---
```linux
[명령어] < [파일명]
```
명령어에 파일명안의 내용을 스탠다드 인풋으로 전달한다.
- 예)
    ```
    listing.txt
    -al
    ```
    ```linux
    ls < listing.txt
    ```
    결과값은 아래의 명령어의 결과값과 같다.
    ```linux
    ls -al
    ```

## 데이터의 흐름의 방향을 컨트롤해 원하는 움직임을 만들어 낼 수 있다.
---
- IO Stream이라고도 부름.

## append
---
```linux
ls -al > result.txt
```
두번실행하면 덮어쓰기가 일어난다.
```linux
ls -al >> result.txt
```
리다이렉션한 결과를 추가(append)한다.
```linux
[명령어] <<[텍스트]
>[input]
>[input]
>[텍스트]
```
input append의 경우
