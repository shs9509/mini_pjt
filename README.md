# mini_pjt
이것저것 만들어보는 프로젝트



### 10/20 Glassmorphism Card

<img src="README.assets/image-20211022203017303.png" alt="image-20211022203017303" style="zoom:50%;" />

#CSS #HTML

- 핵심은 카드의 블러처리와 카드위에 광택처럼주기위해 border-top 을 주는것!
- css 만으로 동적인 페이지를 시도할수있다는 점이 크게 와닿았음
- 남의 코드를 살펴본 결과 상당히 깔끔한 코드로 진행이되서 이를 보고 많이 배웠다.
  - CSS 스타일을 태그 요소기준으로 계층적으로 쌓아가는것
  - CSS를 깔끔하게 함으로서 HTML에도 간단한 코드로 이루어지게 됨



참조: https://www.youtube.com/watch?v=Glsby66vuLA&t=30s

---------



### 10/25 NeonLodingSpinner



<img src="README.assets/image-20211025153045493.png" alt="image-20211025153045493" style="zoom:80%;" />

#CSS #HTML

- 공부 심히 필요!! 
  - webkit
  - animation
    - keyframes



참조: https://www.youtube.com/watch?v=3wRBJESwarQ&ab_channel=OnlineTutorials

--------



### 12/13 3D Glowing Cube

<img src="README.assets/화면 캡처 2021-12-14 200639.jpg" alt="화면 캡처 2021-12-14 200639" style="zoom: 50%;" />



- transform : 요소의 자식 요소가 입체적인 3D 공간에 배치 될지, 요소의 표면에 평평하게 묘사할 지를 결정합니다.
- 애니메이션
  - rotateX : 이것을 -30도로 정해서 아래로 깔아보듯이 나온다.
  - <img src="README.assets/image-20211214202519477.png" alt="image-20211214202519477" style="zoom: 25%;" />  이경우는 -10 도인경우
  - rotateY : 이거를 0도에서 90도로 놓음으로써 4초동안 옆으로 회전하는 에니메이션 생김

- 벽면
  - 벽면의 경우 rotateY를 0,90,180,270 도로 주고 translateZ 150px을 주어서 서로 띄움
  -  translateZ 를 안하면
  - <img src="README.assets/image-20211214202956443.png" alt="image-20211214202956443" style="zoom:33%;" />이렇게 됨



> 어렵다... 공간감각이 살짝 필요한 기술

참조: https://www.youtube.com/watch?v=nOdDtnHWaDo-

---------------
