# TCP 와 UDP 프로토콜 

TCP : 연결형 프로토콜, 데이터의 전송 순서 보장, 데이터 신뢰성 보장 

```sequenceDiagram
    Alice->>John: Hello John, how are you?
    activate John
    John-->>Alice: Great!
    deactivate John
    Alice->>+John: Hello John, how are you?
    John-->>-Alice: Great!
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```



UDP : 비연결형 프로토콜, TCP보다 전송속도 빠르다, UDP 데이터는 데이터 그램 이라고 불린다.

