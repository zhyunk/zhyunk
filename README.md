<!-- header -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
  <a href="#">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=142&section=header&text=🛋️&fontSize=82&animation=twinkling">
        <source media="(prefers-color-scheme: light)" srcset="https://render.gitanimals.org/lines/zhyunk?pet-id=584024399899088575&contribution-view=false" width="850" height="142">
        <img src="https://capsule-render.vercel.app/api?type=transparent&color=auto&height=142&section=header&text=🛋️&fontSize=82&animation=twinkling" alt="🔨-🥲rz"/>    
    </picture>
  </a>
</div>

<!-- introduce project repository -------------------------------------------------------------------------------------------------------------------------------------------->
<details>
<summary align="center"><h3>　📜 　or　<a href="https://github.com/zhyun-project">🔗</a>　</h3></summary>

<details>
<summary><h3>　　simple-board</h3></summary>

<br>
<table align=center>
  <tr><th width=881px>
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
  <tr><th width=881>
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

> 리팩토링 📑
> 1. *`24.04.24 ~ 24.05.18`* - [*프로젝트 구조 변경, 테스트 코드 전체 수정*](https://github.com/zhyun-project/simple-board-02/wiki/🛠%EF%B8%8F-리팩토링-1차-⚒%EF%B8%8F)

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
  <tr><th width=881px>
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
<br>
</details>

<!-- blog posts -------------------------------------------------------------------------------------------------------------------------------------------->
<table align=center>
  <tr><th width=845 height=100 align="center">
    <h3>📖 My blog posts</h3>
  </th></tr>
  <tr><td align=left><span>💡 Recent 5 posts</span></td></tr>
  <tr><td>
<br>

<!-- BLOG-POST-LIST:START -->
- [Ubuntu Desktop - windows로 gui 원격 접속하기 &lpar;rdesktop&rpar;](https://study.zhyun.kim/posts/Ubuntu-Desktop-rdesktop/)
- [Ubuntu Desktop - PDF 편집기 LibreOffice](https://study.zhyun.kim/posts/Ubuntu-Desktop-PDF-%ED%8E%B8%EC%A7%91%EA%B8%B0-LibreOffice/)
- [Ubuntu - 바로가기 &lpar;desktop&rpar; 관련 기록](https://study.zhyun.kim/posts/Ubuntu-%EB%B0%94%EB%A1%9C%EA%B0%80%EA%B8%B0-(desktop)-%EA%B4%80%EB%A0%A8-%EA%B8%B0%EB%A1%9D/)
- [IntelliJ - python 인터프리터 설정](https://study.zhyun.kim/posts/IntelliJ-python-%EC%9D%B8%ED%84%B0%ED%94%84%EB%A6%AC%ED%84%B0-%EC%84%A4%EC%A0%95/)
- [Ubuntu - ssh 접속](https://study.zhyun.kim/posts/Ubuntu-ssh-%EC%A0%91%EC%86%8D/)
<!-- BLOG-POST-LIST:END -->

  <br>
    <div align=right>
      <a href="https://study.zhyun.kim"><picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/study.zhyun.kim_🚀-0A0A0A?style=for-the-badge">
          <source media="(prefers-color-scheme: light)" srcset="https://img.shields.io/badge/study.zhyun.kim_🚀-2f80ed?style=for-the-badge">
          <img alt="blog link" src="https://img.shields.io/badge/study.zhyun.kim_🚀-0A0A0A?style=for-the-badge">
      </picture></a>
    </div>
    </td>
  </tr>

</table>

<br>

<!-- most used top5 & waka time -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
<a href="https://github.com/anuraghazra/github-readme-stats"><picture><source
  media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&theme=github_dark&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300"><source
  media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300"><img
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhyunk&theme=github_dark&custom_title=Most%20Used%20Languages&layout=compact&hide_border=true&count_private=true&include_all_commits=true&langs_count=5&size_weight=0.2&count_weight=0.8&hide=scss,html,javascript,shell,ruby,css&card_width=300"
  align="left" alt="🔨-🥲rz 　 most used top 5"/>
</picture></a><a href="https://wakatime.com/@zhyun"><picture><source
  media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&theme=github_dark&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact"><source
  media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact">
  <img
  alt="🔨-🥲rz 　 waka time"
  src="https://github-readme-stats.vercel.app/api/wakatime?username=zhyun&theme=github_dark&custom_title=Waka%20Time%20⏰%20start%20date%20:%2024.01.03&hide_border=true&layout=compact">  
</picture></a>
</div>


<br>

<!-- capsule-render & git animal -------------------------------------------------------------------------------------------------------------------------------------------->
<div align="center">
<a href="https://github.com/git-goods/gitanimals"><img
  src="https://render.gitanimals.org/lines/zhyunk?pet-id=597095086959652253&contribution-view=false"
  width="420" height="200" alt="🔨-🥲rz　　"/><picture><source
  media="(prefers-color-scheme: dark)" srcset="https://render.gitanimals.org/lines/zhyunk?pet-id=582154833054874760&contribution-view=false"><source
  media="(prefers-color-scheme: light)" srcset="https://render.gitanimals.org/lines/zhyunk?pet-id=583424627266567092&contribution-view=false"><img 
  src="https://render.gitanimals.org/lines/zhyunk?pet-id=575068403528185932&contribution-view=false"
  width="421" height="200" alt="🔨-🥲rz"/>    
</picture></a>
<br>
<a href="https://github.com/kyechan99/capsule-render">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=120&section=footer"  alt="🔨-🥲rz"/></a>
</div>
