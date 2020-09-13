
  > 📝 iOS Swift 정리 - 2020/09/07

    
  # Literal, Identifier, Keyword


 - **Literal**  - 코드 내에서 변하지 않는 데이터 값이다.
  ```swift
  let x = 1
  let y = 2 
  let str = "Swift"
  ```
 > `let x = 1`  1 Literal 이다.<br>
 > `let y = 2`  2 Literal 이다. <br>
 > `let str = "Swift"` "Swift" Literal 이다. <br>

<br>

 - **Identifier (식별자)** - 데이터값의 이름(변수명)으로 사용되는 코드이다.
  ```swift
  let x = 1
  let y = 1 
  let number = 123
  let str = "Swift"
  ``` 
  > x, y, number, str 이 Identifier 이다. 
  
<br>

 - **Keyword (예약어)** - 특정기능이 예약되어 있는 단어이며, Identifier(식별자)로 사용 불가능하다.

  ```swift
  var x = 1
  let y = 2
  ------------
  for i in 10{
      code
  }
  ------------
  if x > y {
      code
  }
  ```
  > var, let, for, if 등 Swift에서 미리 지정해놓은 단어를 말한다.

