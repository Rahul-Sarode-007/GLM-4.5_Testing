## 🚀 AI-Generated Space Shooter Game (GLM 4.5)

This game was created using **GLM 4.5**, an advanced AI model capable of generating modular game code from natural language. The goal was to test the AI's ability to build a real-time, animation-rich, physics-based game architecture — and it delivered.

---

### 🧠 Prompt Used

The entire game was generated using the following single prompt:

Create a space shooter game. The game should demonstrate advanced animations, physics, and modular architecture. Include the following features:

Smooth player movement using velocity, acceleration, and friction (simulate inertia in space).

Advanced enemy AI with three behaviors:
– Seek and follow the player.
– Dodge incoming bullets.
– Patrol random paths.

Particle-based explosion system (with random direction, speed, fade-out effect).

Bullet system: player and enemy bullets with collision detection and sprite-based animations.

Wave system: progressively harder waves with increasing enemy speed, count, and type.

Boss fight mechanic: includes multi-phase health, changing attack patterns, and shield regeneration.

GameEngine, Player, Enemy, Bullet, Particle, UIManager, PhysicsUtils.

Animated parallax background with 3+ layers moving at different speeds.

Fullscreen and responsive: canvas resizes dynamically, maintains aspect ratio.

Game states: Start screen, Pause screen, Game Over, and Level Complete – each with animated transitions.

Add sound effects
