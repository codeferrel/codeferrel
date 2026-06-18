<div align="center">
🛡️ Noe Ferreira

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00F7FF&center=true&vCenter=true&width=520&lines=Informatics+Student+%7C+Cybersecurity+Enthusiast;Ethical+Hacking+%7C+Penetration+Tester" />
<br/>
<a href="https://github.com/codeferrel">
<img src="https://img.shields.io/github/followers/codeferrel?label=Followers&style=for-the-badge&color=00F7FF&labelColor=0D1117"/>
</a>
<a href="https://github.com/codeferrel">
<img src="https://img.shields.io/github/stars/codeferrel?affiliations=OWNER&style=for-the-badge&color=00F7FF&labelColor=0D1117"/>
</a>
</div>

🌐 Connect With Me

<div align="center">
<a href="https://www.linkedin.com/in/noeferreira">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://www.instagram.com/noelferreira04">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>
<a href="https://tryhackme.com/p/noelferreira">
<img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=red"/>
</a>
<a href="https://github.com/codeferrel">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</div>

📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=codeferrel&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F7FF&icon_color=00F7FF&text_color=c9d1d9"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=codeferrel&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F7FF&text_color=c9d1d9"/>
<br/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=codeferrel&theme=tokyonight&hide_border=true&background=0D1117&stroke=00F7FF&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF"/>
</div>

📈 Contribution Graph

<div align="center">
<img width="99%" src="https://github-readme-activity-graph.vercel.app/graph?username=codeferrel&theme=tokyo-night&bg_color=0D1117&hide_border=true&line=00F7FF&point=FFFFFF&color=00F7FF"/>
</div>

🧊 3D Contribution Calendar


Kalender commit dalam bentuk 3D, otomatis ter-update setiap hari lewat GitHub Actions (lihat panduan setup di bawah).



<div align="center">
<img src="https://raw.githubusercontent.com/codeferrel/codeferrel/main/profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="3D Contribution Calendar"/>
</div>
<details>
<summary>⚙️ Cara setup widget 3D ini (klik untuk lihat)</summary>
<br/>

Di repo profil kamu (codeferrel/codeferrel), buat folder .github/workflows/
Buat file profile-3d-contrib.yml dengan isi berikut:


yamlname: GitHub 3D Contribution
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A
          git commit -m "generate 3d contrib" || exit 0
          git push


Push ke GitHub, lalu buka tab Actions di repo → pilih workflow ini → klik Run workflow (sekali manual untuk generate pertama kali)
Setelah selesai, akan muncul folder baru profile-3d-contrib/ isinya beberapa file SVG seperti profile-night-rainbow.svg, profile-night-green.svg, dll
Gambar di atas akan otomatis tampil begitu file itu ada di branch main


</details>

🛠️ Security & Dev Stack

<div align="center">
🛡️ Cyber Security Tools

<br/>
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white"/>
<img src="https://img.shields.io/badge/Nmap-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=portswigger&logoColor=white"/>
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white"/>
<br/><br/>

💻 Programming & Environment

<br/>
<img src="https://skillicons.dev/icons?i=python,cpp,java,javascript,php,mysql,linux,bash,git,github,vscode,docker"/>
</div>

🏆 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=codeferrel&theme=darkhub&no-frame=true&row=1&column=7"/>
</div>

🧠 Current Focus

yamlFocus:
  - Penetration Testing (Web & Network)
  - Bug Bounty Hunting
  - Automation with Python
  - Advanced OSINT Techniques

Learning With:
  - TryHackMe
  - Cisco
  - PortSwigger
  - MerdekaSiber


<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>
</div>
