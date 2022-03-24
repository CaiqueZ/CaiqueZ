-   -- PORTUGUÊS/BR --
- 👋 Olá, Eu sou @CaiqueZ
- 👀 Tenho interesse em > desenvolver
- 🌱 Atualmente estou aprendendo > JS, HTML & CSS
- 💞️ procuro colaborar > "none"
- 📫 Como chegar até mim | Como me encontrar > contato.caiquen@gmail.com
-   \/
-   -- ENGLISH --
- 👋 Hi, I’m @CaiqueZ
- 👀 I’m interested in > to develop
- 🌱 I’m currently learning > JS, HTML & CSS
- 💞️ I’m looking to collaborate on > "none"
- 📫 How to reach me > contato.caiquen@gmail.com

<!---
CaiqueZ/CaiqueZ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- name: generate-snake-game-from-github-contribution-grid
  uses: Platane/snk@v0.0.18
- uses: Platane/snk@master
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # path of the generated gif file
    # If left empty, the gif file will not be generated
    gif_out_path: dist/github-snake.gif

    # path of the generated svg file
    # If left empty, the svg file will not be generated
    svg_out_path: dist/github-snake.svg
