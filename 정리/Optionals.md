> 📝 iOS Swift 정리  
> `optionals`  `optional Type`  `Unwrapping`  `Forced Unrapping`

# Optionals

-----

- Optionals 
  값을 가지지 않아도 되는 형식이다.

  ```swift
  TypeName // Non-Optional Type
  TypeName? // Optional Type
  
  let optionalNum: Int = 0 
  let optionalNum: Int? = nil   
  
  let str: String = nil // 에러 발생
  let str: String? = nil // 사용 가능
  ```

> `nil` 자체로는 추론 할 형식이 없으며 항상 타입 어노테이션으로 타입을 지정해주어야 한다.
> `nil` = 아무것도 저장하지 않겠다는 뜻과 같은 의미이다.

- Forced Unwrapping
  강제로 값을 추출하는 방법이다.

  `Unwrapping` 는 값이 랩으로 포장되어 있다고 생각하고, 실제로 저장된 값이 필요하면 랩을 벗겨야 하며 이러한 과정 말한다.

  ```swift
  var num: Int? = nil
  print(num) // nil 출력
  num = 123 
  print(num) // Optional(123) 출력
  print(num!) // 123 << 강제로 값을 추출
  
  ```

> `var num: Int? = nil` 코드에서는 옵셔널 타입으로 선언해주었기 때문에 `num` 출력시 `Optional(123)` 이 출력된다.
> `num` 뒤에 `!` 를 붙이면 강제로 값을 추출하기 때문에 `Unwrapping` 되어 출력시 `123` 이 출력된다.

⁉️ 중요

1. 옵셔널에 저장되어 있는 값을 사용하려면 값을 언랩핑 해야한다.
2. 닐이 있는 상태에서 강제 추출하면 크래시가 발생한다.
3. 옵셔널 표현식을 언랩핑 하면 넌 옵셔널 타입으로 결과가 리턴된다.



