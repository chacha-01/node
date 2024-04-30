
## HW3

#### 1-1. 변수의 선언시 변수 영역에 식별자로 지정된 공간이 확보됨을 확인할 수 있다.

#### 1-2. 데이터가 데이터영역에 할당되면 데이터는 변수 영역 값이 가리키고있는 주소에 저장됨을 확인할 수 있다.

#### 1-3. 수, 문자열, boolean, Null, Undefined, Symbol은 불변값임을 확인할 수 있다.

#### 1-4. 참조형 데이터가 데이터 영역에 있다면 그 데이터가 가리키는 변수가 변함에 따라 그 값도 변화한다는 것을 확인할 수 있다.

#### 1-5. 참조형 데이터의 프로퍼티를 재할당할 경우 객체의 변수 영역이 가리키는 데이터 영역이 또한 변화하므로 변수 영역 값이 바뀐다는 것을 확인할 수 있다.

#### 1-6. 특정객체의 프로퍼티로 객체가 있는 경우 중첩 참조가 발생한다는 것을 확인할 수 있다.

#### 1-7. 두 변수에 복사가 일어났다면 두 변수는 같은 데이터 영역을 가리킨다는 것을 확인할 수 있다.

#### 1-8. 복사된 객체의 프로퍼티를 변경하더라도 변수가 가리키는 데이터 영역은 원본 객체와 같다는 것을 확인할 수 있다.

#### 1-9. 복사된 객체를 변경하면 원본 객체와 별개의 데이터 영역을 가리키게 된다는 것을 확인할 수 있다.

#### 1-10. 복사된 객체의 프로퍼티만을 수정하여, 원본 객체와 사본 객체가 가리키는 데이터 영역이 같아짐에 따라 원본 객체의 프로퍼티가 달라지는 문제가 발생한다는 것을 확인할 수 있다.

#### 1-11. 객체를 처음부터 다시 만들어 변수에 저장함으로써 문제를 해결할 수 있음을 확인할 수 있다.

#### 1-12. 객체의 얕은 복사를 수행을 확인할 수 있다.

#### 1-13. 예제 1-12에서 만든 객체 복사 함수를 이용해 객체를 복사하고, 불변성을 유지함을 확인할 수 있다.

#### 1-14. 중첩된 객체에 얕은 복사를 수행하면 객체 프로퍼티에 대해 원본의 불변성이 확보되지 않는다는 것을 확인할 수 있다.

#### 1-15. 깊은 복사는 객체 프로퍼티의 내부까지 복사해 원본 객체의 불변성을 유지한다는 것을 확인할 수 있다.

#### 1-16. 객체 프로퍼티에 대해 copyObjectDeep 함수를 재귀적으로 호출해 깊은 복사를 범용적으로 수행한다는 것을 확인할 수 있다.

#### 1-17. 예제 1-16의 깊은 복사의 결과를 확인할 수 있다.

#### 1-18. 객체 -> JSON 문법 -> 깊은 복사 -> 객체로 치환한다. 이때 함수는 JSON 문법으로 변경할 수 없어 복사 과정에서 무시됨을 확인할 수 있다.

#### 1-19. 다음의 세 가지 경우 undefined가 자동으로 부여된다는 것을 확인할 수 있다.
##### - 값을 대입하지 않은 변수에 접근하는 경우
##### - 존재하지 않는 프로퍼티에 접근하는 경우
##### - 함수의 반환값이 존재하지 않는 경우

#### 1-20. 배열의 undefined 요소와 비어있는 요소는 다르다는 것을 확인할 수 있다.

#### 1-21. 비어있는 요소는 배열 메서드의 순회 대상에서 제외된다는 것을 확인할 수 있다.

#### 1-22. typeof null이 object를 반환하는 버그가 있으므로 어떤 변수가 null인지 판별하기 위해선 일치 연산자를 사용해야 한다는 것을 알 수 있다.

#### 2-1. 함수를 이용해 실행 컨텍스트를 구성해보면서 콜 스택에 실행 컨텍스트가 쌓이는 순서를 확인해본다.

#### 2-2. 원본 코드의 출력을 확인해보면서 호이스팅의 개념에 대해서 확인해본다.

#### 2-3. 매개변수를 변수선언과 할당과 동일하다고 간주하여 변환한 코드를 출력해보면서 호이스팅의 개념에 대해서 확인해본다. 결과는 동일하다.

#### 2-4. 호이스팅을 마친 상태로 간주하여 변환한 코드를 출력해보면서 호이스팅의 개념에 대해서 확인해본다. 결과는 동일하다

#### 2-5. 원본코드의 출력을 예상하고 확인하면서 호이스팅의 개념을 복습한다.

#### 2-6. 호이스팅을 마친 상태로 간주하여 변환한 코드를 출력해보면서 호이스팅의 개념에 대해서 확인해본다. 결과는 동일하다 

#### 2-7. 함수 선언문(정의부만 존재)을 함수 표현식(function을 별도 변수에 할당)으로 바꾼 코드의 결과를 출력해보면서 호이스팅의 개념에 대해서 확인해본다. 결과는 동일하다.

#### 2-8. 함수 선언문과 익명 함수 표현식, 기명 함수표현식으로 정의된 세가지 방식을 확인하고, 예상대로 기명 함수인 d()는 외부에서 접근할 수 없어 오류를 일으키는 것을 확인해본다.

#### 2-9. 원본 코드의 출력을 확인해보면서 함수 선언문과 함수 표현식의 차이를 이해한다. sum은 정상적으로 3이 출력되나, 값이 할당되지않은 multiply는 에러 메시지가 출력된다.

#### 2-10. 호이스팅을 마친 상태로 간주하여 변환한 코드를 출력해보면서 호이스팅의 개념에 대해서 확인해본다. 결과는 동일하다.

#### 2-11. 같은 이름의 함수가 함수 선언문으로 추가되었을 때, 실제로 호출되는 함수는 마지막에 할당한 함수이다. 즉 코드의 앞부분에서 숫자를 반환하는 코드를 짰어도 문자열을 반환하는 함수만이 실제로 호출 될 수 있다. 함수 선언문으로 정의한다면, 이러한 전혀 예기치 못한 오작동이 에러메세지도 없이 발생할 수 있다.

#### 2-12. 함수 표현식으로 선언한다면, 만에 하나 전역공간에 같은 이름의 함수가 있어도, 예제 2-11과는 달리 에러메세지를 출력하여 현 코드에 문제가 있다는 사실을 바로 알 수 있다.

#### 2-13. 식별자 a에 접근하려고하지만, 활성화된 inner 컨텍스트의 environmentRecord 에서의 a는 undefined 상태이기에 undefined가 출력되고, 전역 lexicalEnvironment의 a값인 1과 전역 컨텍스트의 environmentRecord의 a값인 1이 출력된다.

#### 2-14. 크롬 브라우저에서의 개발자 도구 콘솔을 이용해 스코프를 확인해본다.

#### 2-15. inner 함수 내부에서 b변수를 호출하면 스코프에 b도 노출되는 것을 확인할 수 있다.

#### 2-16. debugger로 바꾸어 크롬 브라우저에서 스코프체인과 this 정보를 확인할 수 있다.

#### 3-1. this와 window가 브라우저 환경에서 같은 전역 객체를 참조함을 확인할 수 있다.

#### 3-2. Node.js 환경에서 this 와 global 이 같은 전역 객체를 참조함을 확인할 수 있다.

#### 3-3. 브라우저 환경에서 선언된 변수 a가 전역 객체 window 와 this에 속해있음을 확인할 수 있다.

#### 3-4. 브라우저 환경에서 전역 객체 window와 this의 프로퍼티로 변수 a와 b가 접근 및 수정 가능함을 확인할 수 있다.

#### 3-5. 브라우저 환경에서 var로 선언된 전역 변수는 delete로 삭제할 수 없으나, 직접 window 객체에 할당된 프로퍼티는 삭제할 수 있음을 확인할 수 있다.

#### 3-6. 함수가 일반적으로 호출될 때는 전역 객체를 this로 참조하고, 객체의 메소드로 호출될 때는 해당 객체를 this로 참조함을 확인할 수 있다.

#### 3-7. 객체 내부에서 메소드가 직접 호출되거나 대괄호 표기법으로 호출될 때, this는 해당 객체를 참조함을 확인할 수 있다

#### 3-8. 객체의 메소드가 직접 호출되거나 대괄호 표기법으로 호출될 때, this는 메소드가 정의된 현재 객체를 참조함을 확인할 수 있다.

#### 3-9. 함수 내에서 정의된 내부 함수는 기본적으로 전역 객체를 this로 참조하지만, 다른 객체에 할당되어 메소드로 호출될 경우 그 객체를 this로 참조하게 된다.

#### 3-10. 객체 메소드에서 일반 함수로 호출된 내부 함수는 전역 객체를 this로 참조하며, self 변수를 사용하여 내부 함수에서 외부 함수의 this를 참조할 수 있음을 확인할 수 있다.

#### 3-11. 객체의 메소드에서 화살표 함수로 정의된 내부 함수는 외부 함수와 같은 this 즉, 호출한 객체를 참조함을 확인할 수 있다.

#### 3-12. 브라우저 환경에서 setTimeout과 배열의 forEach 메소드 내의 일반 함수는 전역 객체 window를 this로 참조하며, 이벤트 핸들러 함수에서는 해당 핸들러가 부착된 요소를 this로 참조함을 확인할 수 있다.

#### 3-13. 생성자 함수 Cat을 사용하여 choco와 nabi 두 객체를 생성하고, 각 객체는 고유의 이름과 나이 속성을 가지며 공통적으로 '야옹'을 출력함을 확인할 수 있다.

#### 3-14. 일반적으로 호출된 함수는 전역 객체를 this로 참조하며, call 메소드를 사용하여 호출된 함수는 지정된 객체 { x: 1 }를 this로 참조하고 인자를 순서대로 전달받음을 확인할 수 있다.

#### 3-15. 객체의 메소드가 직접 호출될 때는 해당 객체의 프로퍼티 a를 참조하며, call 메소드를 사용하여 다른 객체로 this를 지정할 경우 지정된 객체의 프로퍼티 a와 주어진 인자들을 사용함을 확인할 수 있다.

#### 3-16. apply 메소드를 사용하여 함수나 메소드를 호출할 때, 첫 번째 인자로 전달한 객체가 this로 설정되며, 두 번째 인자로 전달한 배열은 함수나 메소드의 매개변수로 전달됨을 확인할 수 있다.

#### 3-17. 객체에 push 메소드를 호출하여 배열처럼 동작하도록 설정하고, 이후 slice 메소드를 사용하여 객체를 배열로 변환함을 확인할 수 있다

#### 3-18. 함수 a는 가변 인자를 배열로 변환하여 각 인자를 출력하고, DOM 요소들을 선택하여 배열로 변환한 후 각 요소를 출력함을 확인할 수 있다.

#### 3-19. 문자열을 배열 메소드를 사용하여 조작할 때, push 메소드는 길이를 변경할 수 없는 읽기 전용 속성에 할당할 수 없다는 오류가 발생하며, concat 메소드는 새로운 배열을 반환하고, every 메소드는 문자열 전체가 주어진 조건을 만족하지 않음을 확인했으며, some 메소드는 문자열 중 일부가 주어진 조건을 만족함을 확인할 수 있다. map 메소드는 각 문자에 대해 '!'를 추가한 새로운 배열을 반환하고, reduce 메소드는 문자열을 누적하여 새로운 문자열을 생성함을 확인할 수 있다.

#### 3-20. 객체를 배열로 변환할 때 Array.from 메소드를 사용하여 각 프로퍼티 값을 배열 요소로 가져왔음을 확인할 수 있다.

#### 3-21. Student와 Employee 생성자 내에서 Person 생성자를 호출할 때 call 및 apply 메서드를 활용한다. 이를 통해 Person의 프로퍼티와 메서드를 상속받고, 각각의 객체에 새로운 속성을 추가한다. 최종적으로 Student와 Employee 객체를 생성함을 확인할 수 있다.

#### 3-22. 주어진 배열에서 최댓값과 최솟값을 찾아 출력함을 확인할 수 있다.

#### 3-23. 주어진 배열에서 가장 큰 수와 가장 작은 수를 각각 찾아내어 출력함을 확인할 수 있다. Math 객체의 max 및 min 메서드를 사용하여 각각 최댓값과 최솟값을 이전보다 쉽게 구할 수 있었다.

#### 3-24. 주어진 배열에서 가장 큰 수와 가장 작은 수를 각각 찾아내어 출력함을 확인할 수 있다. 펼치기 구문을 사용하여 Math 객체의 max 및 min 메서드를 간결하게 적용했다.

#### 3-25. 함수 func를 생성한 후, bind 메소드를 사용하여 다른 객체와 바인딩된 새로운 함수를 생성하고 호출했다. bind 메소드를 사용하여 함수에 추가적으로 인자를 전달하면 해당 인자가 바인딩된 함수의 매개변수로 사용된다.

#### 3-26. bind 메소드로 생성된 새로운 함수의 name 속성은 원본 함수의 이름을 유지한다.

#### 3-27. 객체의 메소드 내에서 내부 함수를 호출할 때, call 메소드를 사용하여 외부 함수의 this를 전달하거나, 내부 함수를 생성할 때 bind 메소드를 사용하여 외부 함수의 this를 유지함을 확인할 수 있다.

#### 3-28. setTimeout 함수 내에서 메소드를 호출할 때, 바로 호출한 경우와 bind 메소드를 사용하여 호출한 경우에는 this의 참조가 다르게 되어 결과가 달라짐을 확인할 수 있다.

#### 3-29. 화살표 함수 내에서 this는 상위 스코프의 this를 유지함을 확인할 수 있다. 객체의 메소드에서 화살표 함수를 사용하면 메소드가 호출된 객체를 this로 참조한다.

#### 3-30. 메소드 add를 사용하여 sum과 count를 업데이트하고, average 메소드를 사용하여 sum을 count로 나눈 평균을 계산함을 확인할 수 있다.

#### 3-31. 여러 메소드에서 자주 사용되는 배열 및 집합과 관련된 메소드들이다. 이 메소드들은 배열 또는 집합을 순회하거나 조작할 때 유용하게 사용된다. 메소드 호출 시 각각의 메소드가 받는 매개변수와 동작에 대한 설명이 포함되어 있다. 각 메소드는 주어진 콜백 함수를 배열 또는 집합의 각 요소에 적용하며, 선택적으로 콜백 함수 내에서 사용될 this 값도 지정할 수 있다.