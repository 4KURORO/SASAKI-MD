<h1 align="center"> 亗𝑆𝐴𝑆𝐴𝐾𝐼 𝐹𝐴𝑀𝐼𝐿𝑌亗 </h1> 

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>

<h1 align="center"> SASAKI-MD </h1>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=50&pause=1000&color=1BAFBAFF&center=true&width=910&height=100&lines=THANKS FOR CHOOSING+SASAKI-MD+WHATSAPP+BOT;CREATED+BY+亗𝑆𝐴𝑆𝐴𝐾𝐼 𝐹𝐴𝑀𝐼𝐿𝑌亗" alt="Typing SVG" /></a>
  </p>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<p align="center"> 
<img src="https://telegra.ph/file/69a6ade6cf290c7480ce4.jpg" />
<p/>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
  
<p align="center">
<a href="https://github.com/Alp24ni"><img title="Author" src="https://img.shields.io/badge/SASAKI Bot-black?style=for-the-badge&logo=whatsApp"></a>
<p/>
<p align="center">
<a href="https://github.com/Alp24ni?tab=followers"><img title="Followers" src="https://img.shields.io/github/followers/Alp24ni?label=Followers&style=social"></a>
<a href="https://github.com/Alp24ni/SASAKI-MD/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/Alp24ni/SASAKI-MD?&style=social"></a>
<a href="https://github.com/Alp24ni/SASAKI-MD/network/members"><img title="Fork" src="https://img.shields.io/github/forks/Alp24ni/SASAKI-MD?style=social"></a>
<a href="https://github.com/Alp24ni/SASAKI-MD/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/Alp24ni/SASAKI-MD?label=Watching&style=social"></a>
</p>

<h3 align="center">SASAKI WHATSAPP BOT</h3>
<p align="center">
<a href="#"><img title="Creator" src="https://img.shields.io/badge/Creator-亗𝑆𝐴𝑆𝐴𝐾𝐼 𝐹𝐴𝑀𝐼𝐿𝑌亗-BLUE.svg?style=for-the-badge&logo=github"></a>
</a>
</p>
<p align="center">
<a href="https://github.com/Alp24ni"><img title="Author" src="https://img.shields.io/badge/SASAKI-MD-black?style=for-the-badge&logo=Github"></a> <a href="https://whatsapp.com/channel/0029VaoOYCpHgZWcZwhD6V21"><img title="Author" src="https://img.shields.io/badge/CHANNEL-black?style=for-the-badge&logo=whatsapp"></a> <a href="https://wa.me/221768649590"><img title="Author" src="https://img.shields.io/badge/CHAT US-black?style=for-the-badge&logo=whatsapp">
<p/>

# DEPLOY METHODS AND SET-UP
  
### 1. FORK THIS REPO

<a href='https://github.com/Alp24ni/SASAKI-MD/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork This Repo-blue?style=for-the-badge&logo=git&logoColor=white'/></a>
<p align="center">

### 2. GET SESSION_ID BY TEAMS SASAKI

### SESSION ID CODE.

<a href='https://web-qr-64jj.onrender.com/' target="_blank"><img alt='SESSION ID-CODE' src='https://img.shields.io/badge/SESSION ID-CODE-BLUE?style=for-the-badge&logo=git&logoColor=GREEN'/></a>
<p align="center">

#### DEPLOY TO GITHUB

---
• Create a new file [`.github/workflows/deploye.yml`] After created, copy this code👇🏽and paste it there
```yml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */24 * * *'  # Relance toutes les 6 heures

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [18.18.0]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 50590s npm start  # Limite l'exécution à 5h 59m 50s

    - name: Save state (Optional)
      run: |
        ./save_state.sh
```


#### DEVELOPPEUR 💀

<a href="https://github.com/Alp24ni"><img src="https://github.com/Alp24ni.png" alt="Alp24ni"/></a>


<h2 align="center"> Star This Repo If You like SASAKI-MD 🌟
</h2>


## NB: COPY CODE IF YOU WANT BUT DON'T FORGET TO GIVE CREDIT TO ME

<h2 align="center"> 亗𝑆𝐴𝑆𝐴𝐾𝐼 𝐹𝐴𝑀𝐼𝐿𝑌亗 
</h2>

