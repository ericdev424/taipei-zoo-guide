# Taipei Zoo 3D English Guide · 臺北市立動物園 3D 英文導覽

An interactive 3D map for learning animal names in English while exploring a simplified Taipei Zoo.
一個 3D 互動地圖，邊逛簡化版的臺北市立動物園，邊學動物的英文名字。

> **Unofficial student project.** Not affiliated with or endorsed by Taipei Zoo.
> **非官方學習作品**，與臺北市立動物園無關。

## Features · 功能
- 13 areas and 65 animals, each with an English introduction you can listen to
- Search or speak (English or Chinese) to get walking directions
- Tap an animal to hear its name; tap again for a close-up, or turn 360° around it
- Feeding game: guess what each animal eats (pretend feeding only; never feed animals at a real zoo)
- Shuttle-train timetable estimates, guided tour, and the Zoo Song
- Works on phones and tablets; resolution adapts to keep it smooth

## Run locally · 本機執行
The 3D models are loaded from `models/`, so open the page through a web server (not by double-clicking):
```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```
If the models can't load, the page falls back to simpler built-in shapes.

## Credits · 來源
- Animal and area information: [english.zoo.gov.taipei](https://english.zoo.gov.taipei/) (rewritten for learners)
- Park layout is simplified and approximate
- 3D animals and the explorer avatar are original models made in Blender
- Built with [three.js](https://threejs.org/) r128
