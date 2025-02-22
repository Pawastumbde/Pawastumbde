<h1 align="center">Hi 👋, I'm Pawas</h1>

<p align="center">
  <img src="https://github.com/<your-username>/<your-username>/blob/main/github-metrics.svg" alt="GitHub Metrics" />
</p>

## 🔥 Contribution Stats
- **Commit Streaks**: Keep track of my daily commits
- **Contributions Calendar**: Visualizing my activity
- **Most Used Languages**: Analyzing my coding preferences

## 🛠 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Artificial Intelligence](https://img.shields.io/badge/Artificial%20Intelligence-FF6F00?style=for-the-badge&logo=ai&logoColor=white)
![Bots](https://img.shields.io/badge/Bots-00C853?style=for-the-badge&logo=chatbot&logoColor=white)

## 🎥 Anime & Favorites
- **Favorite Genres**: Action, Drama, Sci-Fi, Adventure
- **Top Animes**:
  - Serial Experiments Lain
  - Neon Genesis Evangelion
  - Ghost in the Shell
  - Attack on Titan
- **Favorite Characters**: 
  <img src="https://github.com/<your-username>/<your-username>/blob/main/favorites.png" alt="Favorite Characters" width="500px" />

<p align="center">
  <img src="https://github.com/<your-username>/<your-username>/blob/main/anime-banner.png" alt="Anime Banner" width="800px" />
</p>

## 📊 GitHub Stats
<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=<your-username>&show_icons=true&theme=tokyonight" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=<your-username>&theme=tokyonight" />
</p>

## 🌍 Visitor Count
![Visitor Count](https://komarev.com/ghpvc/?username=<your-username>&style=flat-square)

## 🔧 GitHub Metrics Workflow
```yaml
name: Metrics
on:
  # Schedule daily updates
  schedule: [{cron: "0 0 * * *"}]
  # (optional) Run workflow manually
  workflow_dispatch:
  # (optional) Run workflow when pushing on master/main
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    environment: 
      name: production
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
```
