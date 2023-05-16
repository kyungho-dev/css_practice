### BEM

Block
Element
Modifier

block__element--modifier

클래스 명을 짓는 규칙 같은 것

.card

.card__img

.card__title

.card__description

.card__button--pink

이미지 타이틀 등은 블럭 안에 있는 엘리먼트이므로 __(언더바 두개) 를 이용해서 작성

만약 비슷한 card가 여러개 있다면 (예를들어 색으로 구별된다면)

.card--dark

.card__img

.card__title

.card__description

.card__button--blue

이런식으로 뒤에 --(대시 두개) 하고 구분할 것? 을 추가

근데 만약 버튼이 .card 박스에만 들어있는게 아니고, 어디서나 쓰이는 컴포넌트라면

.button--blue

.button--pink

이런 식으로 해주어야 한다.

또 카드 블록들이 포함돼있는 박스가 있는 경우

.cards__card__title

이런식으로 하는건 올바른 BEM 방식은 아니다(라고 엘리 강사는 생각)

BEM은 컴포넌트 단위로 나눠진다고 생각해야 한다.

그러므로 각각의 card를 기준으로 box를 나눠주는 것이 맞다.

cards 라는 컨테이너 내부에 card 라는 컴포넌트들이 들어있는 것