# basic

# 'Array를 이용한 스택'과 'LinkedList를 이용한 스택'의 공통점

 1) 스택의 입출력 데이터를 가리키는 'TOP' 프로퍼티가 필요하다. 



# 'Array를 이용한 스택'과 'LinkedList를 이용한 스택'의 차이점

 1) 'Array를 이용한 스택'은 하나의 배열을 생성하고, element들을 pop(), push(), peak() .. 함으로써 스택을 구현한다.  
 따라서 객체(ArrayStack)을 생성할 때 
 프로퍼티 'Obect[] stackArray' 와 'int size'가 필요하다.

# 2) 반면 'LinkedList를 이용한 스택'은 'Node' 객체를 통해 구현한다.
 'Node'객체는 내용을 가지고 있는 'data' 프로퍼티와 
 인근 노드의 주소를 참조하는 'nextNode' 프로퍼티로 구성되어 있다.

