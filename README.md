* Math.random 함수 연습용
* data-set 했던 거 연습할 겸 응용해서 쓰기.

* 사이즈는 핸드폰으로 볼 수 있게 핸드폰 viewport 기준으로 하기.
* 사진은 돌릴때마다 랜덤으로 뜨게!
 -> 사진에 이름말고 폴더에 있는 사진 순으로도 부를 수 있나?
 --> 이건 있을 거 같은데 찾질 못함. 다시 찾아보기.

230305 PM9:53 기준
* 주로 함수들을 이용해서 스타일이나 태그를 만들었고,
* 반복문을 이용해서 폴더에 동일한 이름으로 저장한 사진들에 대해 배열을 만듦.
* 최대값은 사진 갯수만큼이니까 배열의 길이로 설정.
* 사진은 누를때마다 랜덤으로 나오게 했음
 -> 다시 누르면 원래 화면으로 돌아오게 했는데 횟수를 지정하고 일정 숫자 이상되면 돌아오게할까 싶기도 함.

* 보완할 점
1. 사진이 다 비율도 다르고 하니까 그냥 뷰포트 기준 전체로 만들었을 때 뷰포트 사이즈에 따라 사진이 일부만 보이는 경우들이 있음
(주로 높이는 짧고 넓이가 기니까 발생하는 문제인듯.)
어느 기기로 보든 뷰포트 기준으로 사진이 딱 맞게 나왔음 좋겠음. 그러려면 비율조정이 필요할 듯.
2. 위에도 썼지만 배열에 사진갯수만큼 만들어넣은 것에 대해 폴더 안에 파일 갯수를 불러오는 법이 있을 듯한대 확인해보기.
3. 지금은 내가 함수를 쓰는게 더 편하지만 다른 방법에도 익숙해야하므로 리터럴을 더 걷어낼 방법에 대해 생각하기.


* 완결내고 나면 @media 해보기.
* 지금 랜덤으로 나오는 함수 응용해서 틀린그림 찾기 만들어보기.
-> 조건
     => 사진은 저장한 사진들 중 4장을 랜덤으로 뽑아서 2번씩 나와야함.
     => 새로고침 시 다른 사진들로 다시 셋팅.