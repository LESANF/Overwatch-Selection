.hero\*32>.image .hero 라는 클래스를 가진 32개의 div를 생성한다 >.image 자식으로 .image div를 가진 것을.

max-width 를 주게되면 해당 크기보다 작아지게되면 반응형으로 만들어짐 최대 가로너비를 정해지면 커질수있는 요소는 700이지만 그이하는 자동으로 줄어든다 그냥 width 쓰면 짤림

가로사이즈가 있고 블록 상태를 만족할때 margin의 좌우가 auot라면 가운데 정렬이된다. margin: 0 auto; 를 쓴다

색상을 헥스코드를 표현할떄 같은값이 반복되면 3개로 줄여쓸수있다 흰색 = #ffffff = #fff

border: 3px solid #fff; 를 사용했기 떄문에 요소의 크기가 3px늘어났다 이런 값을 포함하지않고 지정시켜주려면 box-sizing: border-box; 를 지정하자

기존요소에 transform을 적용했을때 만약 그 요소에 hover등의 속성을 부여하고 hover될떄 transform을 사용한다면 기존 transform을 덮어쓰기 때문에 기존의 변형이 꺠진다 그러니 hover 될떄도 기존 속성들을 추가해줘야 후에도 유지된다.

요소하는 가운데 정렬하기위해 flex를 쓸 수 도 있지만 아까 말했듯이 가로사이즈가 있고 블록이며 margin 좌우를 auto로 잡아주면 가운데정렬이된다
