<!-- header -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
  <a href="https://github.com/zhyunk">
    <img src="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=100&section=header&text=🛋️&fontSize=82&animation=twinkling"/>    
  </a>
</div>

<br>

<!-- introduce project repository -------------------------------------------------------------------------------------------------------------------------------------------->
<details>
<summary align="center"><h3>　📜 　or　<a href="https://github.com/zhyun-project">🔗</a>　</h3></summary>

<details>
<summary><h3>simple-board</h3></summary>

<br>

<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white"/></a>
<br><br>

h2 db를 embedded 형태로 사용하여  
제목과 내용을 관리하는 간단한 형태의 게시판 프로젝트입니다.

<br>

테스트 코드 작성을 익히기 위해 간단한 구조로 설계하였습니다.

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-01">
      <img src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</div>
</details>

<br>

<details>
<summary><h3>board</h3></summary>

<br>

<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="gradle" src="https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="junit" src="https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="java" src="https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="spring boot" src="https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="spring security" src="https://img.shields.io/badge/Spring_Security-6DB33F?style=badge&logo=Spring-Security&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="jwt" src="https://img.shields.io/badge/JWT-000?style=badge&logo=jsonwebtokens&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="redis" src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=badge&logo=redis&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="h2" src="https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white"/></a>
<br><br>

simple-board 프로젝트에  
사용자 관리를 추가한 프로젝트입니다.

<br>  

JWT와 시큐리티를 적용하여 사용자 로그인 및 권한에 따른 접근 제한 구현과  
멀티 모듈 프로젝트 구현이 목표입니다.

<br>

도메인이 2개(사용자, 게시글)이기 때문에 멀티 모듈 구조를 시도해보게 되었고,  
사용자 관리 모듈과 게시글 관리 모듈, 그리고 gateway(discovery) 모듈 순서로 구현하였습니다.

<br>

시큐리티와 JWT가 어렵다고 생각되어 사용자 관리 모듈을 제일 먼저 개발하였고,  
사용자 관리 구현 후 토큰을 이용하는 서비스인 게시글 관리 모듈을 구현하였으며,  
다음으로 gateway 모듈을 구현하여 하나의 "호스트:port"를 통해 모든 서비스에 접근할 수 있도록 구현하였습니다.

<br>

이번 프로젝트에서는 JWT 검증을 각 모듈에서 검증 후 사용하였지만,  
다음 프로젝트에서는 gateway에서 JWT 검증 후 라우팅하도록 구현해보고자 합니다.

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-02">
      <img alt="repository" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
</div>  
</details>


<!-- template ------------------------------------
<hr>
<br>

<details>
<summary><h3>title</h3></summary>

<br>

// spec
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=badge&logo=Gradle&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/JUnit_5-25A162?style=badge&logo=&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Java-ED8B00?style=badge&logo=openjdk&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/Spring_boot_3-6DB33F?style=badge&logo=spring&logoColor=white"/></a>
<a href="https://github.com/zhyun-project/simple-board-01">
    <img src="https://img.shields.io/badge/H2-224DCA?style=badge&logo=h2&logoColor=white"/></a>
<br><br>

// content

<br>

// repository
<a href="https://github.com/zhyun-project/simple-board-02">
    <img alt="repository" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/></a><br><br>

</details>
-->

<br>

</details>

<br>

<!-- blog posts -------------------------------------------------------------------------------------------------------------------------------------------->
<details>
  <summary align="center"><h3 style="color: #000;">📖 My blog posts</h3></summary>

`💡 Recent 5 posts　`

<!-- BLOG-POST-LIST:START -->
- [Jekyll - &lpar;Chirpy&rpar; Rss Feed 설정 변경](https://blog.zhyun.kim/posts/jekyll-chirpy-rss-feed-%EC%84%A4%EC%A0%95-%EB%B3%80%EA%B2%BD/)
- [Github Pages에서 Vercel로 이동하기 - private repository 전환](https://blog.zhyun.kim/posts/github-pages%EC%97%90%EC%84%9C-vercel%EB%A1%9C-%EC%9D%B4%EB%8F%99%ED%95%98%EA%B8%B0/)
- [Hibernate - MySQL에 Enum 필드를 String&lpar;varchar&rpar;로 저장하는 이슈](https://blog.zhyun.kim/posts/hibernate-Enum-%ED%95%84%EB%93%9C%EB%A5%BC-String(varchar)%EB%A1%9C-%EC%A0%80%EC%9E%A5%ED%95%98%EB%8A%94-%EC%9D%B4%EC%8A%88-(mySql-enum-%ED%83%80%EC%9E%85)/)
- [ubuntu - certbot 🤖 무료 ssl 인증서 설치](https://blog.zhyun.kim/posts/ubuntu-certbot!-%EB%AC%B4%EB%A3%8C-ssl-%EC%9D%B8%EC%A6%9D%EC%84%9C-%EC%84%A4%EC%B9%98/)
- [Spring Boot - 멀티 모듈 구성 &lpar;2&rpar; 다른 방법](https://blog.zhyun.kim/posts/Spring-Boot-%EB%A9%80%ED%8B%B0-%EB%AA%A8%EB%93%88-%EA%B5%AC%EC%84%B1-(2)-%EB%8B%A4%EB%A5%B8-%EB%B0%A9%EB%B2%95/)
<!-- BLOG-POST-LIST:END -->

<div align=right>
  <a href="https://blog.zhyun.kim">
    <img src="https://img.shields.io/badge/blog.zhyun.kim_🚀-0A0A0A?style=for-the-badge"/>
  </a>
</div>

</details>

<br>
<br>

<!-- most used top5 & waka time -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
<a href="https://github.com/anuraghazra/github-readme-stats"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&theme=github_dark&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300"/></a>
<a href="https://wakatime.com/@zhyun"><img src="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&theme=github_dark&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact" align="top"/></a>
</div>

<br>

<!-- footer -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
  <a href="#"><img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=180&section=footer&text=🦆-nl-&fontSize=40&fontAlign=92" /></a>
</div>
