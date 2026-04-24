<div align="center">
wulnrydev
  
### Full-stack developer building web apps, backend systems, and Minecraft server tools.

## About

I enjoy building things that are actually useful and easy to maintain over time.

Most of my work revolves around the JavaScript / TypeScript ecosystem. I mainly build web applications with React and Next.js, develop backend services with Node.js, and occasionally work on Minecraft plugins and other server-side tools using Java.

I care about writing clean and structured code, keeping projects maintainable, and focusing on performance where it actually matters.

</div>

## Tech I Use

**Frontend**

* React
* Next.js
* TypeScript
* Tailwind CSS
* Vite
* HTML
* CSS
* JavaScript

**Backend**

* Node.js
* Express.js
* PHP
* REST APIs
* Java

**Databases**

* PostgreSQL
* MySQL
* MongoDB
* Redis

**Other**

* discord.js
* spigot/paper
* Git
* GitHub Actions

## What I Build

* Portfolio websites and landing pages
* Full-stack web applications
* Backend APIs and services
* Discord bots
* Minecraft plugins and server tools

## Contact

* GitHub: [https://github.com/wulnrydev](https://github.com/wulnrydev)
* Web: [https://www.wulnrydev.com](https://www.wulnrydev.com)
* Discord: `wulnrydev`

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
