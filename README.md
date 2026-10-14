<!-- TOP SHARP HORROR HEADER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=354024&height=180&section=header&text=TAK%20DIUNDANG&fontSize=50&fontColor=E5D7C4&fontAlignY=40&font=Pacifico&desc=The%20Uninvited%20%E2%80%94%20A%20Malaysian%20Folklore%20Horror&descSize=18&descAlignY=68&descColor=CFBB99" width="100%" />
</p>

<!-- QUICK LINKS / BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Godot_4.x-889063?style=for-the-badge&logo=godot-engine&logoColor=E5D7C4" alt="Godot 4" />
</p>

---

## OVERVIEW

**TAK DIUNDANG (The Uninvited)** is a slow-burn psychological horror game set in a quiet Malaysian *kampung*. 

You play as a university student returning home for mid-semester break, expecting a quiet holiday with your sister. However, strange oily smudges, missing personal items, and unsettling noises in the dark reveal that a supernatural figure—the dreaded **Orang Minyak**—is stalking the house.

Driven by traditional folklore defenses (*Daun Mengkuang* traps and *Sekam Padi*), you must investigate, defend your home, and unmask the stalker before it's too late.

---

## KEY FEATURES & GAMEPLAY MECHANICS

* **Atmospheric Narrative Pacing:** Spanning across 4 tense days, starting from packing up at the university dorms to surviving midnight encounters in the village.
* **Folklore Survival Traps:**
  * **Mengkuang Leaves (*Daun Mengkuang*):** Thorny natural barriers that slow down the Orang Minyak, rustle upon impact, and break his spell.
  * **Padi Husks (*Sekam Padi*):** Distraction mechanic exploiting the entity's compulsion to stop and count grains.
  * **Kain Batik Stripping:** Rare active tool used to neutralize his invisibility once trapped.
* **Retro Low-Poly Aesthetic:** PS1/Chilla's Art-inspired graphics featuring low-resolution textures, CRT/VHS shaders, and heavy shadow contrast.

---

## TECH STACK & TOOLS

* **Engine:** [Godot Engine 4.x](https://godotengine.org/) (3D / GDScript)
* **3D Modeling & Assets:** [Blender](https://www.blender.org/)
* **Animations:** [Adobe Mixamo](https://www.mixamo.com/)
* **Textures & Graphics:** Photopea / Paint.NET
* **Audio & Sound FX:** Custom squelching, ambient night noises, and CCTV static audio effects

---

## 📁 REPOSITORY & PROJECT STRUCTURE

```text
TAK_DIUNDANG/
├── assets/
│   ├── audio/          # BGM, ambient sounds, and squelch SFX
│   ├── materials/      # Godot 3D materials (normal skin & oily black shaders)
│   ├── models/         # .glb / .gltf files (House, Props, Characters)
│   └── textures/       # Pixelated low-res texture maps (256x256 / 512x512)
├── scenes/
│   ├── characters/     # Player, Kakak, Orang Minyak, NPCs
│   ├── env/            # Kampung House, Warung, Dorm room
│   ├── ui/             # Main menu, CCTV interface, inventory
│   └── levels/         # Day 1 to Day 4 level scenes
├── scripts/            # GDScript state machines, inventory, and AI behaviors
└── default_env.tres
