<center> 
<h1 align="center">Muhammad Fikri Anwar</h1>

<p align="center" style="font-size:30px;">
  <span style="color:#500073;">H</span>ello <br>
  I'm Fikri, an undergraduate Informatics Engineering student.
</p>

<p align="center">
  Get to know more about me ↓
</p>

waka_be815ce4-b908-4bc4-8708-a5608af733c6
name: Work Stats Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ waka_be815ce4-b908-4bc4-8708-a5608af733c6 }}
