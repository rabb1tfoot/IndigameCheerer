# 인디 게임 개발자를 후원하기 위한 웹페이지

개발환경 및 사용기술

java(11)

apache tomcat9.0

springFramework 2.7.2

Mybatis

mysql 8

주요 서비스

- 회원가입 로그인
프로젝트 생성 / 후원
프로젝트 후기, 댓글, 마감등 알람 서비스

서비스 구조

- 프로필
    
    -프로필사진
    -소개
    -대표 웹사이트
    -사용자URL
    -휴대전화
    -주소
    
- 알람
    
    -프로젝트 후원 (크리에이터)
    -목표 달성 (크리에이터) (후원자)
    -댓글 (크리에이터) (후원자 (대댓글))
    -좋아요 (크리에이터)
    -커뮤티니글 (크리에이터) (후원자)
    -프로젝트 마감 (크리에이터) (후원자)
    

- 프로젝트
    - 프로젝트 계획
        
        소개
        예산
        일정
        팀소개
        선물설명
        목표금액
        
        펀딩기간
        
        대표이미지
        
        좋아요
        --본문
        
    - 업데이트
        
        본문
        
        댓글
        
    - 커뮤니티
        
        본문
        
        댓글
        
    - 프로젝트 진행사항
        
        모인금액
        
        후원자(명)
        
    

2.설계 및 구현

테이블

레퍼런스 페이지

[https://tumblbug.com/koreanmonster?ref=메인3D주목할만한프로젝트](https://tumblbug.com/koreanmonster?ref=%EB%A9%94%EC%9D%B83D%EC%A3%BC%EB%AA%A9%ED%95%A0%EB%A7%8C%ED%95%9C%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)[https://tumblbug.com/oguforest?ref=메인2F최근에본프로젝트](https://tumblbug.com/oguforest?ref=%EB%A9%94%EC%9D%B82F%EC%B5%9C%EA%B7%BC%EC%97%90%EB%B3%B8%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)[https://tumblbug.com/discover?category=board-games-and-trpg](https://tumblbug.com/discover?category=board-games-and-trpg)
[https://tumblbug.com/discover?sort=popular&ongoing=onGoing](https://tumblbug.com/discover?sort=popular&ongoing=onGoing) 
[https://tumblbug.com/discover?sort=publishedAt&ongoing=onGoing](https://tumblbug.com/discover?sort=publishedAt&ongoing=onGoing) 
[https://tumblbug.com/discover?ongoing=onGoing&sort=endedAt](https://tumblbug.com/discover?ongoing=onGoing&sort=endedAt) 
[https://tumblbug.com/discover?ongoing=prelaunching](https://tumblbug.com/discover?ongoing=prelaunching)