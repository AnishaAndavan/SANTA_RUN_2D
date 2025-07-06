# 🎅 Santa Run - 2D Endless Runner Game

Santa Run is a 2D endless runner game developed using **Unity**. The player controls Santa Claus, who runs across rooftops, jumping over gaps and avoiding obstacles. The objective is to survive as long as possible by jumping over incoming obstacles.

## 🎮 Features

- 🏃 Smooth endless running using sprite animations (no Unity Animator animations)
- ⬆️ Jump only when the user clicks/taps
- 🏚️ Dynamic ground scrolling using multiple house sprites
- ⚠️ Obstacle spawning with collisions
- 💥 Game over on hitting an obstacle
- ✅ Custom physics for better jump and fall behavior
- 🧠 Simple architecture for easy modification

## 📁 Folder Structure


## 🛠️ How to Run

1. Open the project in Unity (recommended version: **Unity 2020.3+**)
2. Make sure the Santa character has:
   - Rigidbody2D
   - SpriteRenderer
   - BoxCollider2D
3. Place an empty GameObject under Santa’s feet and assign it as `groundCheck` in the `SantaController.cs`
4. Assign the proper **ground layer** in the script and scene
5. Make sure obstacle objects are tagged as `Obstacle`
6. Press Play and enjoy!

## 🎨 Artwork & Assets

All Santa animation frames are **sprite-based**, arranged manually (no Animator Controller animation clips used). You can easily swap or add new sprite frames for running, jumping, and dead states.

## 💡 Controls

- **Mouse Left Click / Tap** – Make Santa jump
- Avoid obstacles and gaps by jumping at the right time

## 🧱 Dependencies

- Unity Physics2D
- Rigidbody2D
- Unity SpriteRenderer



