  <img src="https://skillicons.dev/icons?i=c,cpp,java,python,js,html,css,nodejs,mongodb,mysql,git,github,figma,vercel,netlify&perline=8" alt="Skills" />
</div>

<br />

<details>
  <summary><b>More about how I like to build</b></summary>
  <br />

  - **Frontend:** accessible, responsive interfaces with a focus on clear UX
  - **Backend & data:** APIs, database design, and maintainable application logic
  - **Problem solving:** breaking complex requirements into simple, testable parts
  - **Continuous learning:** experimenting with modern tools while mastering core CS concepts
</details>

## GitHub analytics

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=mddanish-31&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Danish's GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com/?user=mddanish-31&theme=tokyonight&hide_border=true" alt="Danish's GitHub streak" />
</div>

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mddanish-31&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most used languages" />
</div>

## Contribution activity

<div align="center">
  <img src="https://raw.githubusercontent.com/mddanish-31/mddanish-31/output/github-contribution-grid-snake-dark.svg" alt="Animated contribution snake" />
</div>

> The snake is generated automatically by the GitHub Actions workflow below. Its first run will create the image in the `output` branch.

<details>
  <summary><b>Enable the contribution snake</b></summary>
  <br />

  Create `.github/workflows/snake.yml` in your **profile repository** (`mddanish-31/mddanish-31`) and paste:

  ```yml
  name: Generate contribution snake

  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:

  permissions:
    contents: write

  jobs:
    build:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: mddanish-31
            outputs: |
              dist/github-contribution-grid-snake.svg
              dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v4
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ```

  Then run **Actions → Generate contribution snake → Run workflow** once. GitHub will update it daily after that.
</details>

## Let's build something useful

I am always interested in thoughtful engineering conversations, open-source collaboration, and projects that solve genuine problems. Feel free to connect.

<div align="center">
  <sub>Designed with curiosity, consistency, and a love for building.</sub>
</div>
