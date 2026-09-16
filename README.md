<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2E5EAA&height=180&section=header&text=Hai,%20saya%20%5BNama%20Kamu%5D&fontSize=42&fontColor=F7F7F3&animation=fadeIn" />
</p>

<p align="left">
  Web Developer yang membangun aplikasi dengan sentuhan AI/ML —
  dari integrasi LLM ke produk nyata sampai bikin fitur pintar yang kepake.
</p>

<p align="left">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1200&color=2E5EAA&center=false&vCenter=true&width=600&lines=Web+Development+%2B+AI%2FML;Membangun+produk%2C+bukan+cuma+demo;Belajar+in+public+%F0%9F%9A%80" />
</p>

<p align="left">
  <a href="https://instagram.com/USERNAME_IG"><img src="https://img.shields.io/badge/Instagram-@USERNAME_IG-E4405F?style=flat&logo=instagram&logoColor=white" /></a>
  <a href="https://linkedin.com/in/USERNAME_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:email@kamu.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white" /></a>
</p>

---

### Tentang saya

- 🔭 Lagi kerjain: [nama project yang sedang dikerjakan]
- 🌱 Lagi dalami: [contoh: RAG, fine-tuning, Next.js App Router]
- 💬 Bisa diajak diskusi soal: web development, integrasi AI/LLM ke produk
- 📫 Cara menghubungi: [email atau link kontak]

---

### Tech Stack

**Web Development**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />

**AI / ML**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black" />

**Tools**

<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" />

---

### GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=default&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&hide_border=true" height="165" />
</p>

---

### Contribution Snake 🐍

<p align="left">
  <img src="https://raw.githubusercontent.com/USERNAME/USERNAME/output/github-contribution-grid-snake.svg" />
</p>

> Animasi ini otomatis update tiap hari berdasarkan grafik kontribusi kamu.
> Cara aktifin: lihat panduan setup di bagian bawah file ini.

---

<p align="left"><i>Update terakhir: [Bulan Tahun]</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=2E5EAA&height=100&section=footer" />

---

## Cara aktifin animasi Snake (sekali setup)

1. Di repo profile kamu (`USERNAME/USERNAME`), buat folder `.github/workflows/`
2. Buat file `snake.yml` di dalamnya, isinya:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
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

3. Commit dan push. Buka tab **Actions** di repo, jalankan workflow-nya manual sekali (`workflow_dispatch`)
4. Setelah selesai, branch baru bernama `output` otomatis kebuat berisi file SVG animasinya
5. Ganti `USERNAME` di bagian "Contribution Snake" di atas dengan username GitHub kamu — animasinya bakal update sendiri tiap hari
