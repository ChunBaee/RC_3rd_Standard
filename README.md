# RC_3rd_Common
(주) 소프트스퀘어드 의 부트캠프인 '라이징캠프' 3주차 미션 과제입니다.

당근마켓 상품목록 및 상품등록화면 클론입니다.

## 핵심개념

📕 어플에는 각각의 수명주기가 존재하고, 그들을 잘 활용하자.

(onCreate() → onStart() → onResume() → onPause() → onStop() → onDestroy() )

## 진행상황

🚂 새로운 과제를 받고 난 후, 기능 구현 자체는 어렵지 않게 할 수 있었다.

🚂 플로팅 버튼 스피드 다이얼과 오버레이 부분에서 애를 꽤 먹었다.. ~~(공식 홈페이지에도 예시화면만 존재할 뿐 예시코드는 없다 카더라..)~~

🚂 챌린지 미션 같은 경우, 화면들에서 수명주기를 활용해 로그인 여부를 판별하는 식으로 구성했다.

## 에러사항

💢 Floating Action Button 을 클릭 시, 두 개의 작은 버튼이 올라오고, 반투명 오버레이가 덮여야 했다.

→ CardView, FrameLayout & Fragment 등등 상당히 많은 시도를 했다.

💢 위의 과정을 구현한 후에도 하단바는 덮이지 않는 이슈가 발생했다.

## 피드백

🤦🏻 결국 구글링 & 깃허브 등 참고하여 외부 라이브러리를 사용함으로 써 해결했다. ~~( Awesome UI 에도 비슷한 라이브러리가 있었지만, 사용에 필요한 부가 자료가 너무 부족했다..)~~

🤦🏻 해당 이슈는 결국 해결하지 못했다. 새로 받아온 라이브러리의 오버레이 파일도 뜯어보고, 구글링 등등 시도를 해보았지만 해결할 수 없었다고 한다...



![Screenshot_20220111-185218_RC_Standard_3](https://user-images.githubusercontent.com/80454599/163403062-e8c8edc0-a351-4964-8483-deb228c5aa3f.jpg)

![Screenshot_20220111-185234_RC_Standard_3](https://user-images.githubusercontent.com/80454599/163403096-8e03ca42-84d1-47d2-b53c-acfa9edf1cee.jpg)
