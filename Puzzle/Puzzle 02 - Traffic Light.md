---
작성일자: 2016년 5월 19일 목요일  


---


# Puzzle 02 - Traffic Light

![Schematic](./images/02_Traffic_Light_schem.ps.png)

## 소스코드

`delay()` 설명

```
int REDpin = 6;
int GREENpin = 4; 

void setup() {
    pinMode(YELLOWpin, OUTPUT); pinMode(GREENpin, OUTPUT);

    delay(5000);
    
    digitalWrite(YELLOWpin, HIGH); 
    delay(1000);
    
    digitalWrite(YELLOWpin, LOW); 
    digitalWrite(GREENpin, HIGH); 
    delay(5000);
    
    digitalWrite(GREENpin, LOW);
```