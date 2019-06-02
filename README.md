# ChatServer
---

## 소개
- 여러 명이 대화할 수 있는 채팅 서버
- Socket을 이용해서 구현


## 개선할 점: Thread 한계
- 문제
채팅 인원이 추가될 때마다 Thread가 생성되기 때문에 인원이 많아지는 경우에 서버에 문제가 생길 수 있다.
- 해결 방법
NIO, Netty를 활용해 해결할 수 있다.
