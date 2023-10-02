# Python_base

2023.09.28

출력 : print()
- 문자열을 출력하는 명령어

기본 자료형
- 숫자형(Number) : 정수나 실수(숫자로 이루어진 자료형)
- 문자열(String) : 따옴표를 사용('',"") / 따옴표 안에 문자를 넣으면 된다.
- 리스트(List) : 여러 자료를 보관하는 자료형, 자료 안에 순서가 있다.

주석(Comment) : 컴퓨터가 무시한다. (메모용으로 사용 가능) (Ctrl + /)

변수(variable) : 자료를 담는 그릇
- 변수 이름 = 자료
변수 이름 짓기
- 숫자, 알파벳, 언더바(_) 등을 사용
변수 이름 짓기(금지)
- 숫자로 시작하면 안된다.
- 숫자로만 구성되면 안된다.
- 파이썬 문법에서 사용되는 예약어는 안된다.
- 공백 문자( )와 연산자(+,-,& 등)는 안된다.

2023.09.29

연산(숫자)
- (+) : 더하기
  1+2>>>2
- (-) : 빼기
  1-2>>>-1
- (*) : 곱하기
  1*2>>>2
- (/) : 나누기
  1/2>>>0.5
- (//) : 몫 연산자
  1//2>>>0
- (%) : 나머지 연산자
  1%2>>>1
- (**) : 제곱 연산자
  1**2>>>1
  
연산(문자열)
- (+) : 더하기
  ex) print('hi'+'king') -> hiking
- (*) : 곱하기
  ex) print('hi'*3) -> hihihi

인덱스 : 문자열과 리스트 자료형의 특정 원소의 위치, 0부터 시작.

인덱싱 : Index를 이용해서 리스트나 문자열의 특정 위치의 원소를 가져오는 방법
- string/list[index]
- a='abcde' -> print(a[0]) >>> a

슬라이싱 : Index를 이용해서 리스트나 문자열의 일부분을 잘라서 가져오는 방법
- string/list[a(시작인덱스):b(종료인덱스]
- a='abcde' -> print(a[1:3]) >>> bc

= : assign(대입 연산자)
== : equal(등호)

2023.10.01

입력 : input()
- 문자열을 입력하는 명령어
- var=input()

형 변환
- int(integer) : 정수
- float : 실수
- str(string) : 문자열
- list : 리스트

논리 자료형
- 참(True)
- 거짓(False)

비교 연산자
- == : 같다
- != : 다르다
- > : 왼쪽이 더 크다
- < : 오른쪽이 더 크다
- >= : 왼쪽이 같거나 크다
- <= : 오른쪽이 같거나 크다

논리 자료형의 연산
- and (모두 True여야 True)
  print(1==1 and 2==2)>>>True
- or (True가 존재하면 True)
  print(1==1 or 1==2)>>>True
- not (반대)
  print(not 1==1)>>>False

2023.10.02

조건문
if문
- 조건이 True일 때, 명령 실행















