---
layout:     post
title:      "VScode 에서 PYTHON 사용하기"
subtitle:   "왜 난 VS code를 이용하나  "
date:       2019-01-01 23:01:14
author:     "Jun"
header-img: "img/tags/python-bg.jpg"
comments: true
tags: [python]
---

---

main program 개발 tool로 vscode로 정하였다. 가장 큰 이유는 pycharm이 너무 수행하는데 무거워서이다. 그리고 vscode를 사용해보니 여러 가지 언어와 연동해서 사용하기가 용의하다고 판단을 하였다. 물론 단축키를 익히고 사용방법에 익숙하기 까지는 시간이 걸린다. 그럼에도 불구하고 선택한 이유는 아래와 같다. 

#VS code setup



---
#VS code 에서 python setup

---
#VS code 에서 python 실행



#Reference python 사용법
[![image](https://img.youtube.com/vi/M8yVZpeed3Y/0.jpg "프로그램 포기자를 위한 파이썬 - 환경 설정편")](https://www.youtube.com/watch?v=M8yVZpeed3Y)

---
# You tube markdown 하기 

유튜브의 내용을  markdown에서 세련되게 하려면 첨부된 link file 형태로 진행하면된다

```markdown
[![image](image_url "내용")](youtube url)
```
예시
youtube url : https://www.youtube.com/watch?v=M8yVZpeed3Y
image url : https://**img**.youtube.com/**vi**/M8yVZpeed3Y/**0.jpg**

Bold text가 차이나는 부분임

```
[![image](https://img.youtube.com/vi/M8yVZpeed3Y/0.jpg "프로그램 포기자를 위한 파이썬 - 환경 설정편")]
(https://www.youtube.com/watch?v=M8yVZpeed3Y)
```

[![image](https://img.youtube.com/vi/M8yVZpeed3Y/0.jpg "프로그램 포기자를 위한 파이썬 - 환경 설정편")](https://www.youtube.com/watch?v=M8yVZpeed3Y)

[Youtube markdown 하기 ](http://nonamedeveloper.tistory.com/entry/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EC%84%9C%EC%97%90-%EC%9C%A0%ED%8A%9C%EB%B8%8C-%EB%A7%81%ED%81%AC-%EB%A9%8B%EC%A7%80%EA%B2%8C-%EC%B6%94%EA%B0%80%ED%95%98%EA%B8%B0 "youtube markdown")

#Lecture 
[![Havard Data science lecture 커리큘럼](http://cdn2.sph.harvard.edu/wp-content/uploads/sites/5/2015/05/HarvardChan_logo_stack_RGB_Small.png "Harvard datasciencelab 커리큘럼")](https://datasciencelabs.github.io/pages/lectures.html ) 


[![image](https://sites.google.com/a/ajou.ac.kr/data-tree/_/rsrc/1489055664154/deiteo-nyuseu/deiteo-sosig/deiteosilmujadeul-ichucheonhaneundeiteosaieonseuonlainmulyogang-ui13gae/%EC%82%AC%EC%A7%841.png "Data science 추천")](https://70a4597c-a-192fca36-s-sites.googlegroups.com/a/ajou.ac.kr/data-tree/deiteo-nyuseu/deiteo-sosig/deiteosilmujadeul-ichucheonhaneundeiteosaieonseuonlainmulyogang-ui13gae/%EC%82%AC%EC%A7%841.png?attachauth=ANoY7cpJxt8ACR2l1BscNWoJZRccSvUg5T5vx01THp8xTDJw8NWyR5qme3LshCH4ZIXaslxNtpbQdWf-GxBdAfFAqh8n1os-rk2KXjOE95ezYGBJrUrSUzr2U7-D0V1P_vUKLAZcW9Ktsr9wzyrC9tyojlziVPe3_DEz-URQMu6sywHpHc0uYLBxLxrOD1UFmZC6S9OoJDyqmSRQJlSTuhI90GVtXB9XLZQsCqPgestZE2n3SMKk9VVO1PnG07r4SItBFMKorwpBNpvV5lA5UGi-iILqwR1adXA_o2Qzli1IxWMSJO3_08woQamp6GJgyC5RT_Chs3oCK1YiBrvMTtZOzM4bcpvOrUuvmSYSv3Apt31WoWxyXc4%3D&attredirects=0)


<!-- [![image](https://sites.google.com/a/ajou.ac.kr/data-tree/_/rsrc/1489055664154/deiteo-nyuseu/deiteo-sosig/deiteosilmujadeul-ichucheonhaneundeiteosaieonseuonlainmulyogang-ui13gae/%EC%82%AC%EC%A7%841.png "Data science 추천")](https://70a4597c-a-192fca36-s-sites.googlegroups.com/a/ajou.ac.kr/data-tree/deiteo-nyuseu/deiteo-sosig/deiteosilmujadeul-ichucheonhaneundeiteosaieonseuonlainmulyogang-ui13gae/%EC%82%AC%EC%A7%841.png?attachauth=ANoY7cpJxt8ACR2l1BscNWoJZRccSvUg5T5vx01THp8xTDJw8NWyR5qme3LshCH4ZIXaslxNtpbQdWf-GxBdAfFAqh8n1os-rk2KXjOE95ezYGBJrUrSUzr2U7-D0V1P_vUKLAZcW9Ktsr9wzyrC9tyojlziVPe3_DEz-URQMu6sywHpHc0uYLBxLxrOD1UFmZC6S9OoJDyqmSRQJlSTuhI90GVtXB9XLZQsCqPgestZE2n3SMKk9VVO1PnG07r4SItBFMKorwpBNpvV5lA5UGi-iILqwR1adXA_o2Qzli1IxWMSJO3_08woQamp6GJgyC5RT_Chs3oCK1YiBrvMTtZOzM4bcpvOrUuvmSYSv3Apt31WoWxyXc4%3D&attredirects=0) -->

#Reference





