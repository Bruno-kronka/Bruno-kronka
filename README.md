
## Bem-vindo(a) ao perfil do Bruno-kronka 😁

 <div>

   <a href="https://github.com/Bruno-kronka">

   <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Bruno-kronka&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>

   <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bruno-kronka&layout=compact&langs_count=6&theme=tokyonight"/>

</div>

<div style="display: inline_block"><br>

  <img align="center" alt="Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">

  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">

  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">

</div>

 

 <br>

 

  ### Pra conteúdo sobre programação me segue a gente nas redes abaixo!
  

 name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: devemdobro
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<div> 

  <a href="https://www.youtube.com/devemdobro" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>

  <a href="https://instagram.com/devemdobro" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>

 <a href="https://discord.gg/5DVhGKVf4h" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 

  <a href = "mailto:gemeos@devemdobro.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

  <a href="https://www.linkedin.com/in/ricardohdias" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 

 

  ![Snake animation](https://github.com/devemdobro/devemdobro/blob/output/github-contribution-grid-snake.svg)

</div>
