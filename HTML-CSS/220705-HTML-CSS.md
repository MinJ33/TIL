# CSS
---
## Learned
---
1. float
2. flex
3. grid

---
**float**
- 특정한 요소를 왼쪽 혹은 오른쪽에 정렬하고자 할 때 쓰는 속성
- float을 쓰면 다음 요소가 같은 줄에 위치하게 되고, 해당 요소에다가 clear속성을 적용하는 것을 통해서 해당 요소가 다음 줄에 위치하도록 할 수 있다!
- 다음 요소가 `줄바꿈이 되지 않는다`는 특징이 있음
- 새로운 div가 다음줄에 오게 하고 싶다면
    - clear: left -> float: left 속성을 해제
    - clear: right -> float: right 속성을 해제
    - clear: both -> float 속성을 모두 해제

**flex**
```
display: flex;
```
- 기본적으로 flex 를 적용하면, 내부의 요소들은 모두 가로로 정렬
- 가로로 정렬됐을 때: 가로 축이 메인축(justify-content), 세로 축이 교차축(align-items) 
- 세로로 정렬됐을 때: 세로 축이 메인 축(justify-content), 가로 측이 교차축(align-items)

- `메인 축 정렬 (justify-content)`
	- 메인 축이 기본적으로 가로 이므로, 현재는 가로를 기준으로 정렬하고 싶을 때 justify-content 를 사용한다
	- 속성값: center, flex-center, flex-end, space-between, space-around, space-evenly

- `교차 축 정렬(align-items)`
	- 교차 축이 기본적으로 세로 이므로, 현재는 세로를 기준으로 정렬하고 싶을 때 align-items 를 사용한다
	- 속성값: center, flex-start, flex-end, stretch, baseline 

- align-self
	- `자기 자신`을 교차 축으로 정렬하고자 할 때 쓰는 속성


**grid**  
```
display: grid;
```  
- 격자 (바둑판과 같은) 형태로 요소들을 배치할 수 있게 도와줌. 
- 정렬하고자 하는 요소들의 부모 요소에 적용해주어야한다.(단, 정확히 격자를 정의해주어야함  )

## TO DO LIST
1. float 실습 연습하기
2. flex 실습 연습하기 
3. flex를 응용해서 간단한 instagram 만들어보기 



