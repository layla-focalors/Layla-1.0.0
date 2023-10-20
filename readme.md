### HomePage FOR Main Write Layla Language

### Introduction
Layla 1.0.0은 언어 중 하나로서 다음과 같은 특징을 지니는 새로운 언어입니다.  
1. proxy 문법을 활용한 언어 간 변수 공유. 
2. 한 파일에서 다중 파일 작성 후, 컴파일 완료 시 자동 import 추가 및 경로에 파일 나누기
3. 자동 최적화 ( LLM 모델을 활용하여 코드를 자동 최적화합니다. )
4. 한국어 및 다국어 문법 지원 ( 한국어 & 영어 기본값 )
5. 자동 에러 교정 : 자동으로 오류를 교정합니다.
6. 엄격 문법 설정 : 함수 및 변수에 대해 엄격한 검사를 설정하여, c, java, typescript와 같이 이용 가능합니다.
7. 쉬운 문법 : 파이썬보다 쉽습니다.
8. 자연어 코딩 지원 (LLM 기반) : 자연어로 코딩이 가능합니다. EX) "3을 저장하고 출력해줘 > proxy.3 = 3 , out(3)

### Installation 
현재 Landing 중이 아니기 때문에 지원되지 않습니다. 예상 출시일 2y 후

### How to use
Proxy 문법  
```
<method="python">
   import datetime
   proxy.save = datetime.datetime.now()
</python>
<method="HTML">
    <body>
        <head></head>
        <p>{proxy.save}</p>
    </body>
</HTML>
```
