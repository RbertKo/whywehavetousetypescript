# Typescript, 왜 써야할까? 

### (Why we have to use Typescript?)

1. Typescript란?
2. Ecmascript( Javascript, Typescript )
3. 써야하는 이유
4. 쓰지 말아야하는 이유에 대한 생각



## Typescript 란

Typescript란 Microsoft에서 만든 Javascript로 컴파일되는 강타입 슈퍼셋 언어입니다.



## ECMAscript ( Javascript, Typescript )

ECMAscript란 **유럽 컴퓨터 제조사 연합** (European Computer Manufacturers Association) 에서 제안된 스크립트의 표준입니다. 그 때 당시 JScript와 Javascript가 있었고, 브라우저 표준으로 하나를 채택을 해야했기 때문에 둘의 격차를 완화하고 중재하기 위해 나온 표준이 ES입니다. 그리고 ES1을 따르는 자바스크립트가 브라우저 언어 표준으로 채택되었습니다.

그리고, Typescript는 ECMAscript 표준을 따릅니다. 그렇기때문에, Typescirpt를 Javascript의 상위 집합(superset) 언어라고 합니다. 

따라서, Javacript에서 Typescript를 써야하는 상황이 오더라도 Learning Curve는 크지 않으니 안심하셔도 됩니다.



## (본격) 써야하는 이유와 쓰지 말아야하는 이유에 대한 나의 생각

> **"Javascript도 다 되고, TS를 쓴다해도 결국 Javascript로 다시 컴파일 시키는데 왜 굳이 써야할까?"**

> "Typescript를 쓰면 오히려 생산성이 떨어지지않나?"

> "기존 JS 라이브러리들을 써도 문제 없는 건가?"

아마 Typescript를 쓰지 말아야하는 이유를 대라면 다음과 같은 것들이 단점과 함께 왜 써야하는지에 대한 의문으로 대표적이지 않을까 생각합니다.



지금부터 제가 생각하는, TS를 채택한 사람들이 생각하는 이유를 설명하겠습니다.



### 안전성

 [The broken promise of static typing](https://labs.ig.com/static-typing-promise)

위 글은 정적 타입과 동적 타입이 버그 발생 빈도가 별다르지 않다라는 글이니 읽어봐도 좋을 것 같습니다.

물론, 저 역시 타입이 모든걸 완벽하게 막아준다는 생각은 없습니다. 하지만, 정적 타입은 우리에게 자잘한 버그를 동적 타입으로 부터 막아줄 기회를 준다고 생각합니다.

버그는 무조건 개발자가 먼저 발견해야 한다고 생각합니다. 사용자가 

### 유지 보수

### 호환성

### 생태계

### 생산성

### 