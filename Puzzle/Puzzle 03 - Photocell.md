---
작성일자: 2016년 5월 19일 목요일  

---

# Puzzle 03 - Photocell (조도센서)

## 소스코드

`Serial.begin()`, `Serial.println()` 설명

```
int potpin = 0; //set analog interface #0 to connect photocell 
int ledpin=13;

    Serial.begin(9600);//set baud rate as 9600

    Serial.println(val);
```