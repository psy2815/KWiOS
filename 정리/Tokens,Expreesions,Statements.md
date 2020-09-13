   > 📝 iOS Swift 정리 - 2020/09/07

 # Tokens, Expreesions, Statements

  - Tokens  - 문법적으로 더이상 나눌 수 없는 요소이다. ( 식별자, 키워드, 구두점, 리터럴, 연산자 )
  ```swift
 a + b
 ```
 >  a + b는 a, +, b 3개의 토큰으로 구성되어 있다.

  - Expressions (표현식) - 하나 이상의 토큰이 모여 하나의 값을 도출하는 코드이다.
  ```swift
 let x = 1
 let y = 2
 x < y
 x > y
 ```
 > ##### x 는 1 값을 도출 
 
 > ##### y 는 2 값을 도출
 
 > ##### x < y true 값을 도출
 
 > ##### x > y false 값을 도출

  - Statements (문장) - 표현식이 하나 이상 모여 특정 작업을 수행하는 코드이다.
  ```swift
 let str = "Swift"
 let number = 123
 print(str)
 print(number)
 ```
 > ##### str 변수에 문자열 Swift 저장 
 
 > ##### number 변수에 123 저장
 
 > ##### str 변수에 저장된 문자열 Swift 출력
 
 > ##### number 변수에 저장된 123 출력

