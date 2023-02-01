# TCP/ IP 

> 인터넷 통신을 위한 모델이다.
> 
> OSI 7 Layer는 표준 모델이다. 하지만 현실은 인터넷을 위해서 
> 
> 사용하는 모델은 TCP/IP이다.

```mermaid
graph LR
A(네트워크 접속 계층)-->B(인터넷 계층)
B-->C(전송 계층)
C-->D(응용 계층)
```

OSI 7 Layer 와 TCP/IP 비교 

왼쪽 TCP/IP  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 오른쪽 OSI 7 Layer

```mermaid
graph LR
A(네트워크 접속 계층)-->B(물리계층)
A-->C(데이터 링크 계층)
D(인터넷 계층)--> E(네트워크 계층)
F(전송 계층)--> G(전송 계층)
H(응용 계층) --> I(세션계층)
H-->J(표현 계층)
H-->K(응용 계층)
```

