<!-- header -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
  <a href="https://github.com/zhyunk"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=100&section=header&text=🛋️&fontSize=82&animation=twinkling">
        <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=70&section=header&text=　%20🔍&fontSize=52&animation=twinkling">
        <img alt="header 1" src="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=100&section=header&text=🛋️&fontSize=82&animation=twinkling"/>    
    </picture>
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://blog.zhyun.kim/assets/img/transparent.png">
        <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=40&section=header&text=🐥&fontSize=32">
        <img alt="header 2" src="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=40&section=header&text=🐥&fontSize=32"/>    
    </picture>
  </a>
</div>

<br>

<!-- introduce project repository -------------------------------------------------------------------------------------------------------------------------------------------->
<details>
<summary align="center"><h3>　📜 　or　<a href="https://github.com/zhyun-project">🔗</a>　</h3></summary>

<details>
<summary><h3>　　simple-board</h3></summary>

<br>
<table align=center>
  <tr><th width=745px>
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
</th></tr><tr><td>
<br>

h2 db를 embedded 형태로 사용하여 제목과 내용을 관리하는 간단한 형태의 게시판 프로젝트입니다.

테스트 코드 작성을 익히기 위해 간단한 구조로 설계하였습니다.

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-01"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>

  </td></tr>
</table>
</details>

<br>

<details>
<summary><h3>　　board</h3></summary>

<br>
<table align=center>
  <tr><th width=745px>
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
</th></tr><tr><td>
<br>

simple-board 프로젝트에 사용자 관리를 추가한 프로젝트입니다.

<br>  

JWT와 시큐리티를 적용하여 사용자 로그인 및 권한에 따른 접근 제한 구현과 멀티 모듈 프로젝트 구현이 목표입니다.

<br>

도메인이 2개(사용자, 게시글)라서 공부해보고 싶었던 멀티 모듈 구조를 적용해볼 수 있었으며
사용자 관리 모듈과 게시글 관리 모듈, 그리고 gateway(discovery) 모듈 순서로 구현하였습니다.

<br>

시큐리티와 JWT가 어렵다고 생각되어 사용자 관리 모듈을 제일 먼저 개발하였고  
다음으로 사용자 관리 구현 후 토큰을 이용하는 서비스인 게시글 관리 모듈을 구현,    
마지막으로 gateway 모듈을 구현하여 하나의 "호스트:port"를 통해 모든 서비스에 접근할 수 있도록 구현하였습니다.

<br>

> [리팩토링 📑](https://github.com/zhyun-project/simple-board-02/wiki/%F0%9F%9B%A0%EF%B8%8F-%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81-%E2%9A%92%EF%B8%8F)  

<div align=right>
  <a href="https://github.com/zhyun-project/simple-board-02"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>  

  </td></tr>
</table>
</details>


<!-- template ------------------------------------
<br>

<details>
<summary><h3>　　title</h3></summary>

<br>
<table align=center>
  <tr><th width=745px>
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
</th></tr><tr><td>
<br>

// content

<br>

// repository
<div align=right>
    <a href="https://github.com/zhyun-project/simple-board-02"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/Repository%20🔗-2f80ed?style=for-the-badge&logo=github&logoColor=white">
        <img alt="repository link" src="https://img.shields.io/badge/Repository%20🔗-100000?style=for-the-badge&logo=github&logoColor=white"/>
    </picture></a>
</div>

  </td></tr>
</table>
</details>
-->

</details>

<br>

<!-- blog posts -------------------------------------------------------------------------------------------------------------------------------------------->
<details>
  <summary align="center"><h3>📖 My blog posts</h3></summary>

<br>
<table align=center>
  <tr><th align=left width=745px>💡 Recent 5 posts</th></tr>
  <tr><td>
<br>

<!-- BLOG-POST-LIST:START -->
- [Spring Boot - JUnit5 Assertions](https://blog.zhyun.kim/posts/Spring-Boot-JUnit5-Assertions/)
- [Spring Boot - JUnit5 Test 설정](https://blog.zhyun.kim/posts/Spring-Boot-JUnit5-Test-%EC%84%A4%EC%A0%95-%EA%B4%80%EB%A0%A8-%EC%A0%95%EB%A6%AC/)
- [Notepad++ - Explorer Plugin](https://blog.zhyun.kim/posts/Notepad-Explorer-Plugin/)
- [Notepad++ - Template 설정 &lpar;NewFileBrowser Plugin&rpar;](https://blog.zhyun.kim/posts/Notepad-Template-%EC%84%A4%EC%A0%95-(NewFileBrowser-plugin)/)
- [Java - 잘못 사용하고 있던 변수 개념 정리](https://blog.zhyun.kim/posts/Java-%EC%9E%98%EB%AA%BB-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B3%A0-%EC%9E%88%EB%8D%98-%EB%B3%80%EC%88%98-%EA%B0%9C%EB%85%90-%EC%A0%95%EB%A6%AC/)
<!-- BLOG-POST-LIST:END -->

  <div align=right>
    <a href="https://blog.zhyun.kim"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/blog.zhyun.kim_🚀-0A0A0A?style=for-the-badge">
        <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/blog.zhyun.kim_🚀-2f80ed?style=for-the-badge">
        <img alt="blog link" src="https://img.shields.io/badge/blog.zhyun.kim_🚀-0A0A0A?style=for-the-badge">
    </picture></a>
  </div>

  </td></tr>
</table>
</details>

<br>
<br>

<!-- most used top5 & waka time -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats"><picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&theme=github_dark&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300">
        <img alt="most used top 5" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&theme=github_dark&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300" align="top"/>
    </picture></a>
    <a href="https://wakatime.com/@zhyun"><picture align="top">
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&theme=github_dark&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact">
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact">
        <img alt="waka time" src="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&theme=github_dark&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact">
    </picture></a>
</div>


<br>

<!-- footer -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
  <a href="#"><img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=180&section=footer&text=🦆-nl-&fontSize=40&fontAlign=92" /></a>
</div>
