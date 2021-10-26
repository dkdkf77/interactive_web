# interactive_web

콜로소 디자이너를 위한 코딩 : 입문부터 포트폴리오 응용까지

# interactive_web

콜로소 디자이너를 위한 코딩 : 입문부터 포트폴리오 응용까지

## 레이아웃의 기본 원리 편

block = 기본적으로 네모 박스로 생겼고, 크기를 설정 할수 있다 height, width 등

inline = text라 보면 된다. height와 width를 설정해도 변경 사항이 없다.

## 블록 설정 

![스크린샷 2021-10-26 오후 1 21 08](https://user-images.githubusercontent.com/88579497/138811793-9f0583ad-6425-4294-bb0f-a55304acd93d.png)



### display block을 display inline으로 바꾸면?

![스크린샷 2021-10-26 오후 1 22 49](https://user-images.githubusercontent.com/88579497/138811797-104c4796-7b85-449e-b670-dc30993d3124.png)


## block 속성에서 width를 없애면?

부모 요소의 <strong> width </strong> 속성 만큼 늘어나게 된다

<strong>height</strong>는 기본적으로 자기가 가지고 있는 색션 만큼만 가지고 있다.

## 대표 적인 인라인

a, span, strong, en, site

## inline-block?

인라인 속성도 들고 있고 블록 속성도 들고 있다.

## article을 inline-block 속성을 만들고 width: 300px, height: 100px 로 주게 되면?

![스크린샷 2021-10-26 오후 1 42 51](https://user-images.githubusercontent.com/88579497/138811805-e1dda8a1-2236-46bf-9bd5-6f6819f53d4b.png)


<strong> inline 의 특성인 text를 가지고 있으면서 block의 속성도 가지고 있으므로 width와 height를 속성 값으로 줄수 있다 !</strong> 기본적으로 block은 위 아래로 쌓아가는 형식이라면 inline은 옆에 공간이 있을 시
글자 처럼 나란히 배치 된다. inline 요소는 text 베이스 라인이 있다고 생각 하면 된다.

## display : none ?

시작적으로 넣었다 안 넣었다 해주는 것 html에서 사라지는 것은 아니지만 뷰포트에서는 안 보이게는 하지만
시각장애인 컨텐츠에서는 제외가 되므로 혹시 꼭 있어야 하는 그러한 컨텐츠면 주의가 요한다고 한다.
