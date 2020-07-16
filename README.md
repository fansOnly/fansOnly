### Hi there 👋

<!--
**fansOnly/fansOnly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=fansOnly)](https://github.com/anuraghazra/github-readme-stats)

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=fansOnly&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)]

📊 **This week I spent my time on**
<!--START_SECTION:waka-->
```text
name: fansOnly

on:
  schedule:
    # Runs at 12am UTC
    - cron: '0 0 * * *'

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
          USERNAME: <username>
```
<!--END_SECTION:waka-->
