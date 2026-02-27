<div align="center">

# 🚀 Space Shooter — GitHub Contribution Game

[![Update Space Shooter Game](https://github.com/xainy75/gh-space-shooter-/actions/workflows/update-game.yml/badge.svg)](https://github.com/xainy75/gh-space-shooter-/actions/workflows/update-game.yml)

> **Blast through your GitHub contributions in a retro arcade-style space shooter!**  
> Every contribution becomes an enemy ship — destroy them all! 🎮

---

![Space Shooter Game](game.gif)

---

## 🌟 How It Works

| Step | Description |
|------|-------------|
| 📊 **Fetch Contributions** | The GitHub Action reads the contribution history from the repository. |
| 🎮 **Generate GIF** | The [`gh-space-shooter`](https://github.com/czl9707/gh-space-shooter) action turns those contributions into an animated space shooter game. |
| 🔄 **Auto-Update** | The GIF regenerates every day at midnight UTC, so it always reflects the latest activity. |

---

## ⚙️ Setup

1. **Fork or copy** this repository.
2. Make sure **GitHub Actions** are enabled.
3. The workflow runs automatically on a daily schedule — or trigger it manually from the **Actions** tab.

```yaml
- uses: czl9707/gh-space-shooter@v1
  with:
    github-token: ${{ secrets.GITHUB_TOKEN }}
    output-path: 'game.gif'
    strategy: 'random'
```

---

## 🛠️ Tech Stack

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat&logo=yaml&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)

---

<sub>⚡ Powered by <a href="https://github.com/czl9707/gh-space-shooter">czl9707/gh-space-shooter</a> · Updated daily via GitHub Actions</sub>

</div>
