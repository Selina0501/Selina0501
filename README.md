<div align="center">
  <img height="200" src="https://miro.medium.com/v2/resize:fit:1360/format:webp/1*IRGHmiGsa16stedQvIaZfw.gif"  />
</div>

###

<h1 align="center">Hey 👋 What's up?</h1>

###

<p align="left">📌My name is Tim and I'm a frontend developer from Munich.<br>I am motivated to continuously learn new technologies and develop myself. My ability to solve complex problems and my passion for programming make me a valuable member for your team.</p>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Selina0501&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Selina0501&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="54" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="54" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="54" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="54" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="54" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="54" alt="angularjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="54" alt="firebase logo"  />
</div>

###

<h2 align="left">About me</h2>

###

<p align="left">🕷 Creating bugs since 2022<br>🧙‍♂️ Meister in web... / JS<br>🔭 I'm currently learning Vue.js<br>💬 Ask me about IT Security<br>🗂 Check my projects here: www.portfolio.com<br>🎯 My goals: senior full stack developer <br>💼 Available to start a new project<br>📑 My professional path so far -CV<br>🎲 Fun fact: ...</p>

###

<h2 align="left">Let's work together</h2>

###

<p align="left">📨 Drop me a line: tim.neumann@developer.com<br>📞 0157 555 784 105</p>

###

<div align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="44" height="32" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="44" height="32" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/whatsapp/default.svg" width="44" height="32" alt="whatsapp logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg" width="44" height="32" alt="facebook logo"  />
</div>

###
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
V02

###

<h1 align="left">Hey 👋 What's up?</h1>

###

name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
###

<p align="left">📌My name is Tim and I'm a frontend developer from Munich.<br>I am motivated to continuously learn new technologies and develop myself. My ability to solve complex problems and my passion for programming make me a valuable member for your team.</p>

###

<h2 align="left">About me</h2>

###

<p align="left">🕷 Creating bugs since 2022<br>🧙‍♂️ Meister in web... / JS<br>🔭 I'm currently learning Vue.js<br>💬 Ask me about IT Security<br>🗂 Check my projects here: www.portfolio.com<br>🎯 My goals: senior full stack developer <br>💼 Available to start a new project<br>📑 My professional path so far -CV<br>🎲 Fun fact: ...</p>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="48" alt="javascript logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="48" alt="typescript logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="48" alt="react logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="48" alt="html5 logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="48" alt="css3 logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="48" alt="angularjs logo"  />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="48" alt="firebase logo"  />
</div>

###

<h2 align="left">Let's work together</h2>

###

<p align="left">📨 Drop me a line: tim.neumann@developer.com<br>📞 0157 555 784 105</p>

###

<p align="left">Find me on social media</p>

###

<div align="left">
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="44" height="32" alt="linkedin logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="44" height="32" alt="discord logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/whatsapp/default.svg" width="44" height="32" alt="whatsapp logo"  />
  <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg" width="44" height="32" alt="facebook logo"  />
</div>

###
