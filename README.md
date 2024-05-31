<!-- Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=800080&height=120&section=header"/>

<!-- Typing SVG -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=800080&size=35&center=true&vCenter=true&width=1000&lines=Hey+!,+I'm+Luann8;Graduating+in+Software+Engineering+🤓;And+Ethical+Hacker+💀;Welcome!+:%29" alt="Typing SVG" />
</p>

<!-- About Me Section -->
<h2 align="center">About Me</h2>
<p align="center">
  <img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" width="300px" alt="Computer Illustration"/>
</p>
<p align="center">Hello! I'm Luann Pereira Mendes from Rio de Janeiro, Brazil. I'm currently graduating in Software Engineering and I have a keen interest in Ethical Hacking. Welcome to my GitHub profile!</p>

<!-- Skills Section -->
<h2 align="center">Skills</h2>

<div align="center">
  <!-- Backend Skills -->
  <h3>Backend Development</h3>
[![My Skills](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)


  <!-- Frontend Skills -->
  <h3>Frontend Development</h3>
[![My Skills](https://skillicons.dev/icons?i=js,html,css,angular,react)](https://skillicons.dev)


  <!-- Focus Areas -->
  <h3>Focus Areas</h3>
  <img src="https://img.shields.io/badge/.NET-0D1117?style=for-the-badge&logo=dotnet&logoColor=512BD4&labelColor=0D1117" alt=".NET" />
  <img src="https://img.shields.io/badge/-Docker-0D1117?style=for-the-badge&logo=docker&logoColor=1572B6&labelColor=0D1117" alt="Docker" />
  <img src="https://img.shields.io/badge/-Kali-0D1117?style=for-the-badge&logo=Kalilinux&logoColor=1572B6&labelColor=0D1117" alt="Kali" />
  <img src="https://img.shields.io/badge/-Rust-0D1117?style=for-the-badge&logo=rust&labelColor=0D1117&logoColor=F48D42" alt="Rust" />
  <img src="https://img.shields.io/badge/-Golang-0D1117?style=for-the-badge&logo=go&logoColor=1572B6&labelColor=0D1117" alt="Golang" />
</div>

<!-- Stats Section -->
<h2 align="center">GitHub Stats</h2>
<div align="center">
  <img width="55%" src="https://streak-stats.demolab.com?user=Luann8&theme=radical&hide_border=true" alt="GitHub Streak" />
  <img width="37%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Luann8&layout=donut&hide_border=True&theme=radical" alt="Top Languages" />
</div>
<img width="100%" align="center" src="https://github-profile-trophy.vercel.app/?username=Luann8&title=Repositories,Commits&theme=radical&no-frame=true&background=0d1117" alt="GitHub Trophies" />

<!-- Snake Animation -->
<img src="https://github.com/LuigiGF/LuigiGF/blob/output/github-contribution-grid-snake.svg" alt="Snake Animation" />

<!-- Links Section -->
<h2 align="center">Find me on</h2>
<p align="center">
  <a href="https://luann8.github.io/Luann-portifolio/">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-800080?style=for-the-badge&logo=Pinterest&logoColor=white" />
  </a>
  <a href="https://luann8.github.io/Links-Personal/">
    <img alt="Linktree" src="https://img.shields.io/badge/linktree-800080?style=for-the-badge&logo=linktree&logoColor=white" />
  </a>
</p>

<!-- Footer -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=800080&height=120&section=footer"/>

<!-- PHP Code -->
```php
<?php

class Programmer {
    public $name = "Luann Pereira Mendes";
    public $languages = ["Portugues", "English", "Spanish"];
    public $location = "Rio de Janeiro, Brazil";

    public function __toString() {
        return $this->name;
    }
}

if (isset($argv[0]) && realpath($argv[0]) === __FILE__) {
    $me = new Programmer();
    echo $me;
}

?>
