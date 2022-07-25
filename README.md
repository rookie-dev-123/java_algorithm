# 자바관련 알고리즘 문제를 하루에 한문제씩 풀고 정리하는 레파지토리

## 문자열
+ [문자열 압축](https://unique-wandflower-4cc.notion.site/34d04fe0d1d54b2eb6c59819e54f3b1c)
+ [대소문자 변환](https://unique-wandflower-4cc.notion.site/9ec81f7196cf4bbebd347d8fe83528e2)
+ [숫자만 추출](https://unique-wandflower-4cc.notion.site/ce4d92318efd49998e4714f75b696ee9)
+ [가장 짧은 문자거리](https://unique-wandflower-4cc.notion.site/0f47bdf062c24142aba9460711fe5da2)
+ [큰수 출력하기](https://www.notion.so/e6c48a47b0a54715b8ce0e3067e766f7)
+ [문장 속 단어](https://unique-wandflower-4cc.notion.site/ebff02a3cc6d44f6ad3ed173b1c340dd)
+ [단어 뒤집기](https://unique-wandflower-4cc.notion.site/d40ac1b645f44cc6838f25b452754155)
+ [특정 문자 뒤집기](https://unique-wandflower-4cc.notion.site/bf710d0ee1344f21a7a7d1ab1a329c3d)
+ [중복 문자 제거](https://unique-wandflower-4cc.notion.site/8ee4e282296440bc97170ece6ed98b95)
+ [회문 문자열](https://unique-wandflower-4cc.notion.site/9ecb494290d941dab357b480398e9e17)
+ [유효한 팰린드롬](https://unique-wandflower-4cc.notion.site/a69802907f6d4cbdad0f40a909aa6a0f)
+ [백준_아스키코드](https://www.notion.so/_-35186204742a4b58a46f2b4d0a6c069e)
+ [백준_숫자의합](https://unique-wandflower-4cc.notion.site/cb12561bfc0946639e5728017ce73dea)
+ [프로그래머스_정수 내림차순으로 배치하기](https://unique-wandflower-4cc.notion.site/_-9c88616a3e5645c7a8920c5d7f4674fc)
+ [가장 짧은 문자거리 복습](https://unique-wandflower-4cc.notion.site/3e6736dececb415b84e54ec91db36d86)
+ [문자열 압축 복습](https://unique-wandflower-4cc.notion.site/5f73e5f7869f43d3816cbc9643c7efd8)
+


## 배열
+ [공통 원소 구하기](https://unique-wandflower-4cc.notion.site/5095c4a556a34617a7f063df7e017a1b)
+ [보이는 학생수](https://unique-wandflower-4cc.notion.site/efcbc6deb6d9485b8cb6d6a7a5c00bfa)
+ [에라토스테네스 체](https://unique-wandflower-4cc.notion.site/ee96f9db88f5431cac1b8aa57d2870a2)
+ [뒤집은 소수](https://unique-wandflower-4cc.notion.site/35d27eaf199a45f79109a1a9ba75d4bd)
+ [점수 계산 복습](https://unique-wandflower-4cc.notion.site/3e02fce6fe0f4b8394d91b1dbbc081b9)
+ [가위바위보]
+ [격자판 최대합](https://unique-wandflower-4cc.notion.site/77b13425484d4dd9bc7cb79728206cb8)
+ [봉우리]
+ [백준-최소,최대]
+ [백준_배열_최댓값]
+ [백준_숫자의 개수]
+ [백준_평균]
+ [백준_OX퀴즈]
+ [큰 수 출력](https://unique-wandflower-4cc.notion.site/c9d23243d1034b22b394955ed70bb2d0)
+ [피보나치 수열](https://unique-wandflower-4cc.notion.site/1450a8b55b5d42d9b274fbc4754f5118)
+ [등수 구하기](https://unique-wandflower-4cc.notion.site/a0c7febacc534031914541c542bc04fd)

## 정렬
+ [수정렬하기]
+ [수정렬하기2]
+ [수정렬하기3]
+ [백준_소트인사이드]

# 프로그래머스
## Level1
+ [o] 핸드폰 번호 가리기
+ [o] 자연수 뒤집어 배열로 만들기
+ [o] 이상한 문자 만들기
+ [o] 정수 내림차순으로 배치하기
+ [o] 제일 작은수 제거하기
+ [o] 짝수와 홀수
+ [o] 직사각형 별 찍기
+ [o] 콜라즈 추측



# 02월 08일
## 문자열
### 1. 문자열 압축
+ 문자열에서 같은 문자가 연속으로 반복되는 경우 반복된느 문자 바로 오른쪽에 반복 횟수를 표시하는 방법으로 문자열을 압축한다
    + 반복문을 사용하여 같은 문자가 나오지 않을 때까지 검사한다
    + 같은 문자가 나온 경우 count를 1씩 증가시킨다
    + 같은 문자가 나오지 않은 경우 변수에 문자와 count 개수를 연결한다
### 2. 암호
+ 문자 개수의 7개 만큼의 # 과 * 로 구성된 암호를 해제하여 문자신호로 구분한다
    + substring 메서드를 사용하여 문자열을 특정 위치까지 자른다
    + replace 메서드를 사용하여 문자가 #인 경우 1로 , *인 경우 0으로 대체한다
    + parseInt 메서드를 사용하여 2진수를 10진수를 변환한다
    + 10진수를 char로 변환하여 문자로 만든다
    + 문자를 이어 붙인다
  

# 02월 09일
## 문자열
### 1. 숫자만 추출
+ 숫자와 문자가 섞여있는 문자열에서 숫자만 추출한다 단, 숫자 순서그대로 자연수를 만든다
 + 문자열을 char 타입의 배열로 만든다
 + 배열을 순회하면서 데이터를 하나씩 꺼낸다
 + 숫자 여부를 판단하기 위해 Character 클래스의 isDigit 메서드를 사용하였다

### 2. 가장 짧은 문자거리
+ 문자열을 입력받는다 문자를 입력받는다 문자열에서 문자를 기준으로 각 문자의 거리를 구한다
  - 문자와 문자간 거리를 저장할 int 타입의 배열을 선언한다
  -   문자열을 char 타입을 배열로 만든다
  - 문자간 거리를 계산할 변수를 선언하고 1000으로 초기화 한다
    - 왜? 가장 먼 위치에 떨어져 있다고 가정하기 위함
  - 문자열에서 꺼낸 데이터와 문자가 같다면 0으로 저장한다
  - 문자열에서 꺼낸 인덱스의 데이터와 문자가 같지 않다면 1로 저장한다
  - 반복문을 순회하면서 같지 않은 문자가 나올때 마다 문자간 거리를 + 1만큼 증가시켜 준다
  - 문자간 거리를 배열에 저장한다
  - 그런데, 문제의 예시를 보면 문자기준 가장 가까운 거리를 계산하는 것을 확인할 수 있다
  - 따라서 문자열을 역 방향으로 순회하면서 거리를 계산하는 과정도 필요하다
  - 배열의 역순으로 반복문을 돌린다
    - 문자와 일치하는 값이 있으면 0으로 저장한다
    - 문자와 일치하지 않는 경우 기존에 계산해둔 거리 값과 비교한다
    - 기존 거리값이 역순으로 돌면서 검사한 거리값 보다 더 크다면
    - 역순으로 돌면서 검사한 거리값을 저장한다
      - 왜? 문자 기준 가장 가까운 거리를 계산해야 하기 때문
  

# 02월 10일
## 배열
### 큰수 출력하기
- 문제에서 첫번째 수는 무조건 출력한다고 했으므로
- 배열의 0번 인덱스의 값을 ArrayList에 담아 둔다
- 배열의 1번 인덱스부터 순회한다
- 현재 인덱스 기준 인덱스 + 1 한 위치의 값이 더 큰 경우 ArrayList에 담는다


### 보이는 학생
- 맨앞에 있는 학생은 무조건 보일 것이다
- 따라서 볼수 있는 학생수를 저장하는 변수를 1로 초기화 시켰다
- 학생수 만큼 키가 담겨있는 배열을 순회한다
- 첫번쨰 학생은 무조건 보이기 때문에 배열의 1인덱스 부터 탐색한다
- 현재 인덱스의 값 기준 인덱스+1 위치의 값이 더 큰 경우 선생님이 볼수 있는 학생이다
- 따라서 변수에 카운팅을 매겨준다


# 02월 11일
## 배열
### 소수
- 크기가 N인 배열을 선언하고 값을 0부터 N까지 넣어준다
- 반복문을 N까지 돌린다
- 숫자를 하나씩 꺼낸다 (i)
- 안쪽 반복문을 돌면서 i의 크기만큼 게속 더하면서 i의 배수에 해당하는 데이터를 걸러낸다
  - i의 배수에 해당하는 애들은 소수가 될수 없다
    - 왜? 배수가 된다는 것은 i를 약수로 갖고 있다는 의미가 되기 때문
    - 배수를 쳐내기 위해 배열[i] = 1으로 처리한다
  - i를 약수로 갖지 않는 데이터를 카운팅 한다
  

### 뒤집은 소수
- 크기가 N인 String 타입의 배열을 선언한다
- N개의 숫자를 문자타입으로 입력받는다
- 숫자를 입력받은후 StringBuffer 클래스의 reverse 메서드를 사용하여 뒤집은후 다시 배열에 저장한다
- 배열에서 숫자를 하나씩 꺼낸다
- 소수가 되려면 2부터 시작해서 자기 자신 까지의 숫자로 나눴을때 자기 자신을 제외한 다른 숫자로 나눠 떨어지면 안된다
- 바깥쪽 반복문을 돌면서 숫자를 하나씩 꺼낸다
  - 2부터 자기자신 까지 돌면서 나눠떨어지는지 검사한다
  - 나눠떨어지는 경우 primeCount 변수의 값을 1씩 증가시킨다
  - 안쪽 반복문을 다 돈후 primeCount 변수의 값이 1 인 경우
  - ArrayList에 해당 숫자를 담는다
  
#02월 12일
### 점수계산
- 문제를 연속으로 맞히는 경우 1점씩 가산점이 붙는다
- 따라서 맞힌 문제개수를 저장할 변수를 선언하고 0으로 초기화 한다
- 총점을 저장할 변수를 선언하고 0으로 초기화 한다
- 반복문을 돌면서 배열에서 데이터를 꺼낸다
  - 데이터값이 1인 경우 맞힌 문제이다
  - 문제를 맞힐때 마다 맞힌 문제수 만큼 변수에 + 1 해준다
  - 총점을 계산하는 변수에 맞힌 문제수를 더해준다
  - 왜? 문제에서 점수가 계산되는 방식의 규칙을 살펴보면
  - 문제를 연속으로 맞히는 경우 맞힌 문제 개수가 변수가 된다
  - 따라서 맞힌 문제개수를 총점을 구하는 변수에 누적하여 더해준다
  - 문제를 틀리는 경우 맞힌 문제 개수를 저장하는 변수를 0으로 초기화 시킨다


### 가위바위보
# 02월 14일
- A가 낸 패를 담을 배열을 선언한다
- B가 낸 패를 담을 배열을 선언한다
- A가 낸 패와 B가 낸 패를 비교하여 이겼을때 졌을때 비겼을때를 판별한다

# 02월 15일
### 격자판 최대합
- 격자판의 가로 크기 , 세로 크기 (n)을 입력받는다
- 격자판의 n x n 너비 만큼 데이터를 입력받아 배열에 저장한다
- 2차원 배열의 각 행의 합 , 각 열의 합 , 정방향 대각선의 합 , 역방향 대각선의 합을 구해 가장 큰 값을 찾는다


# 02월 16일
### 봉우리 최대합
- 입력받은 n의 크기만큼
- 가로 x 세로 격자를 2차원 배열로 만든다
- 2차원 배열에 데이터를 입력받는다
- 각 인덱스를 돌면서 인덱스의 데이터 기준 상 , 하, 좌 , 우 인덱스에 있는값이 기준 값보다 크거나 같으면 해당 인덱스는 봉우리가 될수 없다
- 봉우리의 개수를 구하라


# 02월 17일
### 백준 - 브루트포스 - 블랙잭
- 카드의 개수와 숫자 M이 주어진다
- 3개의 카드를 뽑는다
- 더한 숫자의 합이 M을 넘지 않으면서 M에 최대로 가까운 합을 구한다


# 02월 18일
### 백준 - 브루트포스 - 덩치
- N명의 사람수가 주어진다
- 각 사람의 몸무게와 키가 주어진다
- 사람의 덩치 등수를 구한다

### 내가 생각한 풀이 과정
- 2차원 배열을 생성한다 (N행 2열)
  - 왜? N 명의 사람이 전부 키와 몸무게를 갖기 때문
  - 즉 , 각 행 마다 두개의 열로 구성되 있다
- 2차원 배열에 데이터를 입력받는다
- 2중 반복문을 돌린다
- 각 행별 열 데이터를 추출하여 값을 비교한다
  - 조건: 키와 몸무게가 전부 다음 행의 데이터 값보다 커야 한다
  - 조건을 만족하는 경우 등수를 + 1 시킨후 출력한다
  - 왜? 첫번째 행의 열데이터를 검사하므로
  - 다음 행의 열데이터보다 현재 행의 열 데이터가 크면 내 등수가 높아진다
  

# 02월 19일
## 백줌 - 브루트포스 영화감독숌
### 내가 생각한 풀이 과정 - 1.
- N을 입력받는다
- N -1 한 값을 문자열로 형변환한다
- 문자열 666 앞에 N-1한 문자열을 붙인다

### 문제점
- N이 500일때 문제에서 제시한 값과 일치하는 값이 나오지 않았다

### 내가 생각한 두번째 풀이 과정 - 2.
- N을 입력받는다
- N번째로 작은지 판단해야 한다
- - 따라서 cnt 변수를 선언하고 0으로 초기화 한다
- - cnt와 N이 같지 않을때 까지 반복문을 돌린다
  - - cnt를 1씩 증가시킨다
  - - cnt를 문자열로 변환하여 666이 포함되는지 검사한다

### 개선할 점
+ 구글링해서 다른 사람 코드를 참고했다 
+ 왜 이런방식으로 풀어야 하는지 더 고민 필요

+ 흠..
+ 666을 포함하고 있는 문자열이여야 한다
+ 그런데 N번째로 작아야 한다
+ 따라서 카운팅할 변수를 선언한다 (cnt)
+ 반복문을 돌면서 cnt가 N과 같지 않은지 검사한다
+ + 같지 않으면 N이 666을 포함하고 있는지 검사한다
 + + 포함하면 cnt를 1씩 증가시킨다
  + + 근데 N은 왜 증가시켜야 하는가?...
  


# 02월 20일
## 잘된점
+ 백준 배열 관련 알고리즘 2문제 풀고 정리

## 배운점
+ [백준 최소,최대 풀이과정 정리 및 회고](https://unique-wandflower-4cc.notion.site/_-7aa755e505804299a82b3aca0e1d24ed)
+ [백준_최댓값 풀이과정 정리 및 회고](https://unique-wandflower-4cc.notion.site/_-_-f01a915fabb64e09914f59bcf37d02de)



# 02월 21일
### 잘된점
+ 백준 정렬 관련 알고리즘 한문제 풀고 정리

## 배운점
+ [백준 수정렬하기 풀이과정 정리](https://unique-wandflower-4cc.notion.site/1d74ffbd838c42bd81a732eaabb1c406)


# 02월 22일
### 잘된점
+ 백준 정렬 관련 알고리즘 한문제 풀고 정리
+ 백준 배열 관련 알고리즘 한문제 풀고 정리
## 배운점
+ [백준 수정렬하기2 풀이과정 정리](https://unique-wandflower-4cc.notion.site/2-3db098ff2e8244e6be1f868aed523d4b)
+ 시간복잡도에 대해 고민했다
+ 배열에 숫자를 입력받지 않고 ArrayList를 사용했다
+ StringBuilder 클래스를 사용하여 문자열이 지속적으로 변경되는 경우 불필요한 String 객체가 생기는 것을 막았다
  + 왜? 프로그램 성능이 저하될 수 있기 때문
---
+ [백준 숫자의개수 풀이과정 정리](https://unique-wandflower-4cc.notion.site/_-dbf95db5ea64451babc324d6fc67d9b6)
+ 숫자 3개의 곱 결과에 0 부터 9까지 숫자가 몇번 들어가 있는지 카운팅 한다
+ 숫자데이터를 String으로 변환하고 char 타입의 배열로 만든다
+ 2중 반복문을 사용하여 배열에서 데이터를 꺼내 0 부터 9까지 숫자와 일치하는 경우 카운팅한다
+ 숫자끼리 비교하기 위해 charArray[j] - '0'을 사용하였다


# 02월 23일
## 백준 알고리즘 정렬
### 잘된점 
+ 백준 정렬 관련 알고리즘 한문제 풀고 정리
### 배운점
+[수정렬하기3 풀이과정](https://unique-wandflower-4cc.notion.site/3-5efd609e40d1445b815dd2b1b3938be6)


# 02월 24일
## 백준 알고리즘 배열
### 잘된점
+ 백준 배열 관련 알고리즘 한문제 풀고 정리
### 배운점
+  [나머지 풀이과정](https://unique-wandflower-4cc.notion.site/_-7251a54093fa4f199b72e4e206082714)

## 자바 알고리즘 배열 강의
### 잘된점
+ 배열 관련 알고리즘 한문제 풀고 정리
### 배운점
+ [임시반장 정하기 풀이과정](https://unique-wandflower-4cc.notion.site/11-ee610f4d0a98468f991122f65a35bfbc)


# 02월 25일
## 백준 알고리즘 정렬
### 잘된점
+ 정렬관련 알고리즘 한문제 풀고 정리
### 배운점
+ [소트인사이트 풀이과정](https://unique-wandflower-4cc.notion.site/_-e0e9ba4d3da44d63b13f98e87e595091)

# 02월 26일
## 백준 알고리즘 배열
### 잘된점
+ 배열관련 알고리즘 한문제 풀고 정리
### 배운점
+ [평균 풀이과정](https://unique-wandflower-4cc.notion.site/_-c14a52a0536045ef86feab4cccb04410)

# 02월 27일
## 백준 알고리즘 배열
### 잘된점
+ 배열관련 알고리즘 한문제 풀고 정리
### 배운점
+ [OX퀴즈 풀이과정](https://unique-wandflower-4cc.notion.site/_OX-b5bb270b44e142ce9e86b3d130d63e0b)

# 02월 28일
## 자바 알고리즘
### 배운점
+ 프로그래머스 피로도 문제 진행중

# 03월 03일
## 자바 알고리즘
### 잘된점
+ 백준 문자열 아스키코드 문제 풀고 정리

### 배운점
+ [백준_아스키코드 풀이과정](https://unique-wandflower-4cc.notion.site/_-35186204742a4b58a46f2b4d0a6c069e)


# 03월 05일
## 자바 알고리즘
### 잘된점
+ 백준 문자열 숫자의 합 문제 풀고 정리

### 배운점
+ [백준_숫자의합 풀이과정](https://unique-wandflower-4cc.notion.site/cb12561bfc0946639e5728017ce73dea)


# 03월 07일
## 자바 알고리즘
### 잘된점
+ 문자열 대소문자 변환 문제 풀고 정리
+ 백준 숫자의 합 문제 다른 방법으로 풀이

### 배운점
+ [문자열 대소문자 변환](https://unique-wandflower-4cc.notion.site/9ec81f7196cf4bbebd347d8fe83528e2)
+ [백준_숫자의합](https://unique-wandflower-4cc.notion.site/cb12561bfc0946639e5728017ce73dea)


# 03월 08일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 문장 속 단어 찾기 문제 풀고 정리
+ 프로그래머스 정수 내림차순으로 배치하기 문제 풀고 정리

### 배운점
+ [문장 속 단어](https://unique-wandflower-4cc.notion.site/ebff02a3cc6d44f6ad3ed173b1c340dd)
+ [프로그래머스 정수 내림차순으로 배치하기](https://unique-wandflower-4cc.notion.site/_-9c88616a3e5645c7a8920c5d7f4674fc)


# 03월 09일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 단어뒤집기 문제 풀고 정리

### 배운점
+ [단어 뒤집기](https://unique-wandflower-4cc.notion.site/d40ac1b645f44cc6838f25b452754155)


# 03월 10일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 두문제 폴고 정리

### 배운점
+ [특정 문자 뒤집기](https://unique-wandflower-4cc.notion.site/bf710d0ee1344f21a7a7d1ab1a329c3d)
+ [중복 문자 제거](https://unique-wandflower-4cc.notion.site/8ee4e282296440bc97170ece6ed98b95)

# 03월 11일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 두문제 풀고 정리
+ replace 와 replaceAll 차이점 정리 및 실습

### 배운점
+ [회문 문자열](https://unique-wandflower-4cc.notion.site/9ecb494290d941dab357b480398e9e17)
+ [유효한 팰린드롬](https://unique-wandflower-4cc.notion.site/a69802907f6d4cbdad0f40a909aa6a0f)

# 3월 16일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 한문제 풀고 정리
### 배운점
+ [숫자만추출 다른 방식으로 풀어보기](https://unique-wandflower-4cc.notion.site/ce4d92318efd49998e4714f75b696ee9)

# 3월 17일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 한문제 풀고 정리
### 배운점
+ [가장 짧은 문자 거리](https://unique-wandflower-4cc.notion.site/3e6736dececb415b84e54ec91db36d86)

# 3월 18일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 한문제 풀고 정리
### 배운점
+ [문자열 압축 복습](# 3월 17일
## 자바 알고리즘
### 잘된점
+ 문자열 관련 한문제 풀고 정리
### 배운점
+ [가장 짧은 문자 거리](https://unique-wandflower-4cc.notion.site/3e6736dececb415b84e54ec91db36d86))