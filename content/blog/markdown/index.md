---
title: 깃헙을 위한 마크다운 
description: "markdown"
---


# 문자
## Headers
\# 개수에 따라 헤더 단계 조정 가능 1~6개 까지  
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```
## Italic
`*이렇게 강조합니다*` >> *이렇게 강조합니다*  
`_이렇게 강조합니다_` >> _이렇게 강조합니다_  

## Bold
`**굵은 글씨**` >> **굵은 글씨**   
`__굵은 글씨__` >> __굵은 글씨__

## 조합형
`_You **can** combine them_` >> _You **can** combine them_

## 인용
\> 인용합니다     
   > 인용합니다



# 리스트
```
* 목록
  * 하위목록

1. 순서
    1. 순서입니다
    1. 순서에요
```  
> 순서에서 숫자는 의미 없음

# 코드

* 코드 위 아래로 \``` 붙인다.
   > 사용 언어를 참조하도록 넣을 수도 있다   
     사용법 : \```java    coding... ```   
      
    ```java
    new String("String");
    ```

*  문맥에 코드 넣기 \` 코드 \`   
   설명하다가 `new ZoneDateTime()` 언급하고 싶어


  
    

# 링크

## 링크하기   
[GitHub](http://github.com)

## 인용부를 통한 링크 

클릭을 누르면 링크 가능 [클릭][1]  
<br>

[1]: http://okshok.github.io        "내블로그"

```
클릭을 누르면 링크 가능 [클릭][1]  

[1]: http://okshok.github.io        "내블로그"
```







# 기타

## 특수 문자 처리  
'\\' 사용 
예를들어 #을 사용하고 싶을 경우   
\# 샾을 사용합니다



