# Support Server(지원 서버)

+ Discord Server(디스코드 서버) : Unsupported service(지원되지 않는 서비스)
+ Github Issue(깃헙 이슈) : https://github.com/sejin0104/sejinjin-lang/issues

# English(Translation may not be accurate)
# Sejinjin-Lang

+ This is a very simple(?) code with nothing to say.

+ Note: This language uses Korean. You will need to type in Korean, so we recommend copying and pasting the code.

# Grammar

When you start your code, you should always write `세찐찐이가` and at the end you should write `뭔소리냐ㅋㅋ`

# Example

```
세찐찐이가
기억해라 hello = Hello, world
말해라 (hello)
뭔소리냐ㅋㅋ
```

Interpretation: This means that the hello variable is designated as Hello, world and the variable value of hello is output.

# Print

Must be written as```말해라 {variable}```

example : `말해라 (hello)`

# Variable

Must be written as ```기억해라 {variable} = {value}```

warning : Variable values ​​must be specified unconditionally

# Loop

Must be written as ```반복해라 {number} {code}```

example : ```반복해라 10 말해라 (hello)```

# Variable Deepening

Add a specific value to a variable with ```더해라 {variable} {value}```

A string temporary value is added followed by a number (int) temporary addition.

Subtract a specific value from a variable with ```빼라 {variable} {value}```

Caution: Not used within strings

Set the variable to a specific value ```정해라 {변수명} {값}```

# How to run

```
from sjlang import *

file_path = input("Enter the file path to load: ")

run_from_file(file_path)
```

Regardless of the extension of the code, just specify the location!

For example, It doesn’t matter if it’s test.txt

library is ```pip install sjlang==1.2``` Please proceed with the Rohu installation!

pypi link : https://pypi.org/project/sjlang/

# 한국어
# 세찐찐랭

+ 진짜 할말이 없는 아주 간단한(?) 코드입니다

# 문법

코드를 시작할때는 항상 `세찐찐이가` 라고 하고 마지막에는 `뭔소리냐ㅋㅋ` 이라고 적어야 합니다

# 예제

```
세찐찐이가
기억해라 hello = Hello, world
말해라 (hello)
뭔소리냐ㅋㅋ
```

해석 : hello 변수를 Hello, world로 지정하고 hello의 변수값을 출력한다는 뜻입니다

# 출력

```말해라 {변수명}``` 으로 작성해야 합니다

예 : `말해라 (hello)`

# 변수

```기억해라 {변수명} = {값}``` 으로 작성해야 합니다

주의 : 변수 값은 무조건 지정해야 합니다

# 반복문

```반복해라 {횟수} {구문}``` 으로 작성해야합니다

예 : ```반복해라 10 말해라 (hello)```

# 변수 심화

```더해라 {변수명} {값}``` 으로 변수에 특정값을 더합니다

문자열일시 값을 뒤에 추가 숫자(int) 일시 덧셈이 됩니다

```빼라 {변수명} {값}``` 으로 변수에 특정값을 뺍니다

주의 : 문자열 내에 사용 안됨

```정해라 {변수명} {값}``` 으로 변수를 특정값으로 정합니다

```기억해라```로도 가능

# 실행방법

```
from sjlang import *

file_path = input("불러올 파일 경로를 입력하세요: ")

run_from_file(file_path)
```

코드의 확장명은 상관없이 위치 지정만 해주세요!
test.txt여도 상관 X

라이브러리는 ```pip install sjlang==1.2``` 로 설치후 진행해주세요!

pypi 링크 : https://pypi.org/project/sjlang/
