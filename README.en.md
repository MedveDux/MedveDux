<!-- MedveDux · profile README · terminal edition · EN (русская версия: README.md) -->

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff41&height=200&section=header&text=MedveDux&fontSize=72&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=%24%20whoami%20%E2%86%92%20Mikhail%20Mikhailovsky%20%C2%B7%20PhD%20student%20at%20MSUPE&descAlignY=58&descSize=20" width="100%" alt="MedveDux — $ whoami → Mikhail Mikhailovsky · PhD student at MSUPE"></p>

<p align="right"><a href="README.md"><img src="https://img.shields.io/badge/language-%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-161b22?style=for-the-badge&labelColor=0d1117&logo=googletranslate&logoColor=00ff41" alt="Переключиться на русскую версию"></a></p>

<p align="center"><a href="https://github.com/MedveDux"><picture><source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=00FF41&center=true&vCenter=true&width=600&height=48&lines=%24+whoami;Mikhail+Mikhailovsky+%C2%B7+MedveDux;%24+cat+~%2F.plan;science+%2B+code%3A+from+idea+to+release;%24+make+medvedux;make%3A+%27medvedux%27+is+up+to+date."><img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=1A7F37&center=true&vCenter=true&width=600&height=48&lines=%24+whoami;Mikhail+Mikhailovsky+%C2%B7+MedveDux;%24+cat+~%2F.plan;science+%2B+code%3A+from+idea+to+release;%24+make+medvedux;make%3A+%27medvedux%27+is+up+to+date." alt="$ whoami → Mikhail Mikhailovsky · MedveDux · $ cat ~/.plan → science + code: from idea to release"></picture></a></p>

<p align="center"><img src="https://komarev.com/ghpvc/?username=MedveDux&style=for-the-badge&color=161b22&label=visitors" alt="visitors"> <img src="https://img.shields.io/badge/MSUPE-PhD_student-161b22?style=for-the-badge&logo=academia&logoColor=00ff41&labelColor=0d1117" alt="MSUPE · PhD student"> <img src="https://img.shields.io/badge/%C3%89cole_42-alumnus-161b22?style=for-the-badge&logo=42&logoColor=00ff41&labelColor=0d1117" alt="École 42 · alumnus"></p>

<p align="center"><img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" alt=""></p>

## `$ whoami`

<img align="right" width="220" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" alt="Developer at a desk with monitors">

Hi! I'm **Mikhail Mikhailovsky** — **Misha** to friends, **MedveDux** on GitHub. The handle comes from "медведь", the word for bear: I work calmly, thoroughly, and all the way to release.

- PhD student at **MSUPE** (a university of psychology & education) — actively growing as a researcher
- **École 42** alumnus — peer-to-peer, no teachers. C/C++ track: from my own libc to 3D raycasting
- I love low-level work: `C`, pointers, `Makefile`, my own `printf`
- I take my projects all the way to release: versions, installers, changelogs, real users
- Currently: science, backends in **Go**, tools in **Python**, embedded experiments

```c
/* about.c — built at École 42: norminette approves, so does peer review */
#include <stdio.h>

typedef struct s_dev
{
    const char  *name;
    const char  *alias;
    const char  *edu[2];
    const char  *focus[3];
    const char  *langs[6];
    const char  *motto;
}   t_dev;

static const t_dev  me = {
    .name  = "Mikhail Mikhailovsky",
    .alias = "MedveDux",
    .edu   = {"PhD student, MSUPE", "École 42 alumnus"},
    .focus = {"science", "backend", "tools"},
    .langs = {"C", "Go", "Python", "Dart", "Java", "C++"},
    .motto = "tools that just work",
};

int main(void)
{
    printf("Hi, I'm %s (%s). I write %s, think in pointers, and fear no Makefile.\n",
        me.name, me.alias, me.langs[0]);
    return (0);
}
```

## `$ cat ~/research.log`

```bash
medvedux@dev:~$ cat ~/research.log
[status]   PhD student at MSUPE · actively pursuing research
[mode]     research in parallel with development
[tooling]  code as a research instrument: data, prototypes, automation
```

<p align="center"><i>Science isn't a separate tab for me — it's the other half of the job: hypotheses, experiments, writing. Development helps science with prototypes and data processing, and the scientific mindset helps development: measure, don't guess.</i></p>

### `$ ls ~/ecole42`

<img align="left" width="280" src="gif.gif" alt="ASCII matrix in a terminal">

**École 42** — peer-to-peer, no teachers: your code is reviewed by fellow students, and "it almost works" is not accepted.

Alumnus. The C/C++ track — from my own libc to 3D raycasting: strings and memory, processes and pipes, threads and mutexes, sorting with the fewest operations, C++ modules. That's why C is my top language and why I like to know what happens under the hood.

<p align="center"><sub>$ make re · 2021 → 2022 · 0 teachers, ∞ peer review</sub></p>

<p align="center"><img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" alt=""></p>

## `$ cat ~/.skills`

<p align="center"><img src="https://skillicons.dev/icons?i=c,cpp,go,python,java,dart,flutter,js,html,postgres,docker,linux,bash,git,github,vim,vscode,androidstudio&perline=10" alt="C, C++, Go, Python, Java, Dart, Flutter, JavaScript, HTML, PostgreSQL, Docker, Linux, Bash, Git, GitHub, Vim, VS Code, Android Studio"></p>

| Layer | Tools |
|:--|:--|
| Low level | `C` · `C++` · `Makefile` · `CMake` — pointers, processes, threads, raycasting |
| Backend | `Go` · `PostgreSQL` · `Docker` + `docker-compose` · SQL migrations |
| Mobile | `Dart` / `Flutter` · `Java` (Android) |
| Desktop & tools | `Python` · `NSIS` · `Batch` · `Shell` |
| Games | `Go` + `Ebiten` · `C` |
| Embedded | `ESP32` · `nanopb` / Protocol Buffers |
| Web & bots | Telegram Mini Apps · `HTML` / `JavaScript` |
| Science | research · data · prototypes · experiment automation |

## `$ git log --oneline`

```bash
medvedux@dev:~$ git log --reverse --date=format:%Y --format="%ad  %s%d"
2021  init: joined GitHub, C piscine at École 42
2022  feat(c,cpp): the C/C++ track — from my own libc to raycasting 3D, C++ modules
2022  feat(web,android): web technologies and a first Android app
2024  feat(dart): Flutter and mobile development
2025  feat(go): backends in Go + PostgreSQL + Docker
2026  feat(release,embedded): v1.0 releases, ESP32 experiments (HEAD -> main)
```

### `$ uptime`

```bash
medvedux@dev:~$ uptime
 up 5 years since 2021-09 · PhD student at MSUPE · École 42 alumnus
 load: science · Go backends · Python tools · embedded
```

<p align="center"><i>Building something in Go or Python right now — <a href="https://t.me/MedveDux">ping me on Telegram</a> if you have an idea or a question.</i></p>

<p align="center"><img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" alt=""></p>

## `$ neofetch`

<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=MedveDux&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&ring_color=00ff41&custom_title=%24%20git%20stats%20--all"><img src="https://github-readme-stats.vercel.app/api?username=MedveDux&show_icons=true&include_all_commits=true&hide_border=true&bg_color=ffffff&title_color=1a7f37&icon_color=1a7f37&text_color=24292f&ring_color=1a7f37&custom_title=%24%20git%20stats%20--all" height="165" alt="GitHub stats"></picture> <picture><source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=MedveDux&hide_border=true&background=0d1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&currStreakNum=c9d1d9&sideNums=c9d1d9&sideLabels=c9d1d9&dates=8b949e&stroke=30363d"><img src="https://streak-stats.demolab.com/?user=MedveDux&hide_border=true&background=ffffff&ring=1a7f37&fire=1a7f37&currStreakLabel=1a7f37&currStreakNum=24292f&sideNums=24292f&sideLabels=24292f&dates=57606a&stroke=d0d7de" height="165" alt="GitHub streak"></picture></p>

<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=MedveDux&layout=compact&langs_count=8&hide=objective-c&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&custom_title=%24%20cat%20%2Fproc%2Flangs"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MedveDux&layout=compact&langs_count=8&hide=objective-c&hide_border=true&bg_color=ffffff&title_color=1a7f37&text_color=24292f&custom_title=%24%20cat%20%2Fproc%2Flangs" alt="Top languages"></picture></p>

<!-- The snake appears after the first run of .github/workflows/snake.yml (branch output) -->
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MedveDux/MedveDux/output/github-snake-dark.svg"><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MedveDux/MedveDux/output/github-snake.svg"><img src="https://raw.githubusercontent.com/MedveDux/MedveDux/output/github-snake.svg" width="100%" alt="Contribution snake"></picture><br><sub>The bear feeds the snake commits.</sub></p>

## `$ ping medvedux` · get in touch

```bash
medvedux@dev:~$ ping medvedux
PING medvedux (t.me/MedveDux): 56 data bytes
64 bytes from medvedux: icmp_seq=1 ttl=∞ time="will reply as soon as it compiles"
--- medvedux ping statistics ---
1 packets transmitted, 1 received, 0% packet loss
```

<p align="center"><a href="https://t.me/MedveDux"><img src="https://img.shields.io/badge/Telegram-%40MedveDux-161b22?style=for-the-badge&logo=telegram&logoColor=00ff41&labelColor=0d1117" alt="Telegram @MedveDux"></a> <a href="https://vk.com/medve_dux"><img src="https://img.shields.io/badge/VK-medve__dux-161b22?style=for-the-badge&logo=vk&logoColor=00ff41&labelColor=0d1117" alt="VK medve_dux"></a> <a href="https://github.com/MedveDux"><img src="https://img.shields.io/badge/GitHub-MedveDux-161b22?style=for-the-badge&logo=github&logoColor=00ff41&labelColor=0d1117" alt="GitHub MedveDux"></a></p>

<p align="center">Happy to chat.</p>

<details>
<summary><code>$ sudo make me a sandwich</code></summary>
<p>Okay. Seriously though, the fastest way to discuss anything is <a href="https://t.me/MedveDux">Telegram</a>.</p>
</details>

<p align="center"><img src="https://user-images.githubusercontent.com/74038190/216649417-9acc58df-9186-4132-ad43-819a57babb67.gif" width="200" alt="Cat with a laptop"><br><i>If any repository was useful to you — leave a ⭐. The bear will notice and appreciate it.</i><br><br><code>Continue? [Y/n] █</code></p>

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff41&height=120&section=footer&animation=twinkling" width="100%" alt=""></p>
