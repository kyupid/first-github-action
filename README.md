목표: 벨로그에 올라오는거 감지해서 자동으로 리포에 올리기   
부제: 정기적으로 작동하는 크롤러만들기

- 전에 만들었던 [이거](https://github.com/kyupid/markdown-extractor)좀 이용하면 될듯

1. 매일 특정시간에 내 벨로그 페이지를 체크한다.

2. 페이지를 체크할때 이미지에 있는 div 클래스로 들어가서 `<a href>`가 오늘 날짜(YYmmdd)가 있는지 체크한다.
 ![2021-08-22_21-51-21](https://user-images.githubusercontent.com/59721293/130355929-269e644c-eafd-4585-84b9-36281a4e0f72.jpg)

3. 체크했을 때 있으면 그 포스트를 스크랩한다. (변수에 잠깐 넣어둔다?)

4. 어찌어찌해서 깃헙에올린다
