
# Vitaex Game Concept

![image](https://github.com/user-attachments/assets/d4c62b1b-818a-4595-91f6-751a08315a48)

> [!info]
> **Vitaex** is a portmanteau of Latin *vitam* (life) + *explorare* (to explore) -- "to explore life." A 2D side-scrolling pixel-art sci-fi game built with Python + Pygame. Hand-drawn frame-by-frame pixel art in Paint.net.

---

## Story

The player controls a **simple alien citizen** from the **lower class** of his homeworld. Two species coexisted for centuries, sharing technology and resources to prosper together.

Without warning, thousands of **invader ships** descended at hypersonic speeds -- tearing holes in the atmosphere, firing lasers at cities, dropping soldiers everywhere. Mother ships arrived bringing more.

The invader leader's motive: he planned all along to seize the planet's resources and **eliminate the perceived threat** of the other species entirely, claiming the relationship degraded over decades of disputes.

The protagonist's goal: reach a **robot factory** where a new **mechanized suit** is being built -- one that could help him escape and explore other planets. 

---

## Game Aspects

### Levels

| Level | Setting | Theme |
|-------|---------|-------|
| **0** | Title / Menu | Logo, Voyager spacecraft animation drifting in space, "Press any key" |
| **1** | Side-scrolling shooter | Parallax space/city, **Rubin enemies** that walk, shoot, chase |
| **2** | Industrial factory | Platformer with **hazards** -- presses, steam pipes, lasers, cables, a Guardian boss |

### Player

- **Controls:** WASD / Arrows to move, Q to toggle weapon, W / Up to jump, E to place mine, Space to shoot
- **Health:** Represented by **bullet count** (max 10). Enemies drop +2 bullets on kill
- **Ability:** Place a mine (20s cooldown) that explodes on contact
- **Animations:** 17 states -- idle, walk, pre-jump, jump, landing, each with armed/unarmed and shooting variants


[![Spritesheet Preview](https://github.com/user-attachments/assets/df0e65d3-e7e2-49a3-a871-98b6322a91d5)](https://github.com/user-attachments/assets/df0e65d3-e7e2-49a3-a871-98b6322a91d5)
*(Click the image to view the full-size 3819x57 spritesheet!)*


### Enemies & Hazards

```
VITAEX ENEMIES

Rubin Enemy
  - Walks toward player
  - Shoots at intervals
  - 4 bullet health

Guardian
  - Stationary defender
  - Shoots while gate opens
  - Guards Level 2 gate

Hazards (Level 2)
  - Press: ceiling crusher, kills on contact
  - Pipe: steam burst on timer
  - Laser: beam cycles 4s on/off
  - Cable: electrified, kills on touch
  - Gate: opens when player approaches; triggers Guardian
```

### Visual Style

![Character Spritesheet](https://github.com/user-attachments/assets/60fd7ed1-b7e4-4199-9b8d-a1c13058945f)

- **Pixel art**, frame-by-frame animation via spritesheets
- **Parallax scrolling** -- multi-layer backgrounds at different speeds
- **Resolution:** 1136 x 638
- **60 FPS** gameplay

### Tech Stack

- **Python** + **Pygame** -- custom physics, collision detection, variable-jump gravity
- **Paint.net** -- all sprites hand-drawn
- **Scrolling:** screen follows player at map boundaries, max width ~5690px

---

## Tone

**Betrayal and survival.** A story about diversity, broken trust, and the will to keep going when your world falls apart.


---

## Demo Gameplay

### Level 1

![gameplay](https://github.com/user-attachments/assets/f75d8736-cb7d-4e46-bb3c-0feb714ce1ef)

### Level 2

![gameplay3](https://github.com/user-attachments/assets/74d17cfe-72dd-4161-9db8-8c23b9f79bcb)


