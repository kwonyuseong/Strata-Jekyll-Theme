---
layout: post
title: 삽질
categories: diary
tags:
- jekyll
---
<img src="/images/it/shovel/console.jpg" class="fit image">

# 오늘 한 삽질...

오늘은 테마를 바꿔 보려 고 했습니다.

바로 이걸로요 [데모 링크](https://jaehee0113.github.io/console/)
[테마 홈 링크](http://jekyllthemes.org/themes/console/) 구경할때 막 누르다 보면 메뉴창에서 요 블로그 주인님 포스트로 갑니다.
가면 여러 외국어를 추가 할 수 있고 검색 가능에 페이지 네이션 덧글 등의 기능이 있어 사용 해보고 싶어 졌습니다.

[이 블로그를 다시 참고하여](https://ianjang.github.io/blog/2017/04/01/jekyll_Template_%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0/)
열심히 따라 하믄 된다...
그런데 `bundle install`을 해도 똑같은 에러가 남아있다.. 나는 임시 방편이지만 gemfile의 버전을 지정하는 코드를 싹다 날려버렸더니 되어서 이렇게 사용하고 있다. 언제 고장날지는 모르겠지만 ㅎ

그렇게 따라하면..... 깃허브 레파지토리 설정에 이렇게 에러가 뜬다...(이미지는 인터넷에서 퍼온거)
<img src="https://user-images.githubusercontent.com/13817521/29779238-38f56648-8c12-11e7-9324-4b1385dfb95b.png" class="fit image">그래서 하나도 수정하지 않은 파일을 fork 해서 해보니 또 같은 에러가 뜬다.. ㅜ

설정파일을 보자 웬지 로컬호스트 포트번호가 신경쓰인다 4000 으로 바꿔보자
<img src="/images/it/shovel/01_origin.jpg" class="fit image">  응 안되

내 주소인 kwonyuseong.github.io 로 바꿔보자
<img src="/images/it/shovel/shovel.jpg" class="fit image">응 안되

....

설명서를 읽지 않는 한국인의 습관을 버려야 합니다.
<img src="/images/it/shovel/02_console2.jpg" class="fit image">
npm 이 뭐드라.... 앗 아앗 [Node.js 설치](http://blog.danggun.net/4147)를 안했던거 같은 데 이전 테마때 설치안하고 넘어갔던걸 깨달음
[그와중에 gulp 할때 도움되어보이는 블로그](http://programmingsummaries.tistory.com/356)

그만 알아보자..
<img src="/images/it/shovel/05_stop.jpg" class="fit image">

# 결론
1. 루비에 rake 란게 있던데 둘러보자
2. 이 아저씨 코딩 너무 잘해서 못따라가겟다
3. 환경설정 버전 체크좀 잘하자
