# Movie recommendation

## **Interstellar**

<img src="https://i0.wp.com/www.heyuguys.com/images/2014/09/Interstellar-Poster-slice.png?fit=1000%2C646&ssl=1" width="650">

|  | MOVIE INFO |
|----------|:-----------------|
| **장르** | Action & Adventure, Science Fiction & Fantasy |
| **개봉** | 2016.01.14 재개봉, 2014.11.06 개봉 |
| **감독** | 크리스토퍼 놀란 |
| **출연** | 매튜 맥커너히(쿠퍼), 앤 해서웨이(브랜드), 제시카 차스테인(머피) |

### Synopsis

> “우린 답을 찾을 거야, 늘 그랬듯이”

세계 각국의 정부와 경제가 완전히 붕괴된 미래가 다가온다.  
지난 20세기에 범한 잘못이 전 세계적인 식량 부족을 불러왔고, NASA도 해체되었다.  
이때 시공간에 불가사의한 틈이 열리고, 남은 자들에게는 이 곳을 탐험해 인류를 구해야 하는 임무가 지워진다.  
사랑하는 가족들을 뒤로 한 채 인류라는 더 큰 가족을 위해, 그들은 이제 희망을 찾아 우주로 간다.  
그리고 우린 답을 찾을 것이다. 늘 그랬듯이…  
(출처: 네이버 영화)


### Official Trailer
공식 예고편은 [여기]( https://www.youtube.com/watch?v=2LqzF5WauAw "Official Trailer")를 클릭하세요.

### _INTERSTELLAR_ QUOTES
* > STAY (쿠퍼 | 매튜 맥커너히)
* > 순순히 어두운 밤을 받아들이지 마오. 노인들이여, 저무는 하루에 소리치고 저항해요. 분노하고, 분노해요. 사라져가는 빛에 대해. (Dr. 만 | 맷 데이먼)
* > 사랑은 시공간을 초월하는 우리가 알 수 있는 유일한 것이에요. 이해는 못하지만 믿어보기는 하자구요. (아멜리아 | 앤 해서웨이)

***********

### Program: Showing some quotes
```python

quote = {'1':'"STAY" (쿠퍼 - 매튜 맥커너히)',
         '2':'"순순히 어두운 밤을 받아들이지 마오. 노인들이여, 저무는 하루에 소리치고 저항해요. 분노하고, 분노해요. 사라져가는 빛에 대해." (Dr. 만 - 맷 데이먼)',
         '3':'"사랑은 시공간을 초월하는 우리가 알 수 있는 유일한 것이에요. 이해는 못하지만 믿어보기는 하자구요." (아멜리아 - 앤 해서웨이)',
         'q': '감사합니다.'}

while True:

    if len(quote) != 0:
        usr_input = input("총 {}개의 명대사가 있습니다. {}~{} 사이의 숫자를 입력하세요(중지:q): ".format(len(quote)-1, '1', len(quote)-1))
        if usr_input not in quote:
            print('숫자를 잘못입력하셨습니다. 다시 입력하세요.'); print(); continue

        if usr_input == '1':
            print(quote['1'], end='\n'); print()

        elif usr_input == '2':
            print(quote['2']); print()

        elif usr_input == '3':
            print(quote['3']); print()

        elif usr_input == 'q':
            print(quote['q']); break

    

```


