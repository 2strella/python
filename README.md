# Markdown
### 12. 수학 수식 - LaTeX 구문
$$
\sum_{i=1}^{n}i = \frac{n(n+1)}{2}
$$

$x^2 + y^2 = z^2$

---
### 11. 같은 페이지 내 이동
[같은 페이지 내 이동](# 같은 페이지 내 이동)
---
### 10. 표
|NO|함수|의미|
|:------------------:|------------------|------------------|
|1|lower()|문자열을 소문자로 전환|
|2|upper()|문자열을 대문자로 전환|
---
### 9. 글자 강조
일반 글씨  

**굵은 글씨**  

*이탤릭체*

---
### 8. 
![beach](https://github.com/2strella/python/blob/34742a1b2f5b372b5cb2eff4e2ef24ceead681c6/summer.jpg)
---
### 7. 하이퍼링크
[PCWK](https://cafe.daum.net/pcwk)
---
### 6. 가로 : -, * 3개 이상
---

### 5. 목록
### 하위목록
1. 아이템 1
2. 아이템 2

#### 순서 목록
1. 1번
2. 2번
3. 3번

#### 무순서 목록
* 1
- 2
+ 3
---
### 4. 코드블록
```
def main():
    count = int(input("몇개의 상품을 구매하십니까?"))
    totalPrice = 0

    for num in range(1, count+1):
        price = 1000
        print('2+1 상품입니다')

        if (num % 3 == 0):
            pass
        else:
            totalPrice += price
    print('총 가격은 {}원 입니다'.format(totalPrice))

main()
```
---
### 3. 인용상자
# 같은 페이지 내 이동
> 여기에 인용할 내용 기입  
> 빈 줄이 없으면 자동으로 인용 상자에 포함

인용상자 종료. (인용상자로부터 한 줄 띄우기)

---
### 2. 헤더
#을 1개부터 6개까지 6단계로 사용할 수 있음 (h1~h6)

# java
## HTML
### CSS
#### Javascript
##### JSP
###### Python
---
### 1. 문단 구분을 위한 개행 (space 2개)
무더운 여름날 수영장에 빠져봅시다.  
그냥 버티기엔 너무 더움..
