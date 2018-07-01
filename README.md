# basic

# 'Array를 이용한 스택'과 'LinkedList를 이용한 스택'의 공통점

 1) 스택의 입출력 데이터를 가리키는 'TOP' 프로퍼티가 필요하다. 

# 'Array를 이용한 스택'과 'LinkedList를 이용한 스택'의 차이점
  
 1) Array 스택 -> 하나의 클래스('ArrayStack')로 스택을 구현한다.  
  -'Array를 이용한 스택'은 하나의 배열을 생성하고, element들을 pop(), push(), peak() .. 함으로써 스택을 운영한다.
    Node객체처럼 배열을 따로 클래스로 만들어 운영하면, 
    배열을 생성할 때마다 스택을 하나 더 생성하는 것과 같다. -> 의미 x
    
 2) LinkedList 스택 -> 두 개의 클래스('LiskedListStack'과 'Node')로 스택을 구현한다.
  -'LinkedList를 이용한 스택'은 'Node' 객체를 이용하여 스택을 운영한다.

