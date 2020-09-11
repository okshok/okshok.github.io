---
title: 자바 날짜
description: "Hello World"
---

### 타임존

자바 8 이상부터는 ZoneId를 사용한다. 단순히 TimeZone만 사용하면 되는데 왜 그런 것일까? 

이유는 정치적, 역사적인 또는 summberTime으로 동일한 TimeZone에서도 offSet이 달라질 수 있기 때문이다. 그래서 ZoneId는 시간의 흐름에 따라  offset이 달라지는 ZoneRule 객체를 갖고 있다.

예를 들어

대한민국의 표준시는 현재는 UTC +9다. 1954~1961년까지는 UTC+8:30이었다. 출생년도가 58년 개띠인 사람의 데이터를 넣을 때는 offSet을 +8:30으로 넣어야 된다는 의미
 
### 좀더 자세히 알아보자

JRE는 Time Zone Database (TZDB)를 갖고 있다. 여기에는 각 지역마다  오프셋,  Daylight Saving Time(이하 DST) 를 어떻게 처리할지에 대한 기준 정보가 들어있다. 그 지역정보가 Asia/Seoul 등의 ZoneId 다

### ZoneId

지역정보를 갖는 abstract 객체로 

### ZoneOffset

ZoneId를 통해 구현하지만 UTC+09:00 등의 OFFSET정보만 가지고 있다. 

### ZoneRegion




https://stackoverflow.com/questions/32437550/whats-the-difference-between-instant-and-localdatetime