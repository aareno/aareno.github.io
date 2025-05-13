---
layout: project
type: project
image: img/startmenu.png
title: "In the Shadows"
date: 2025
published: true
labels:
  - Unity
  - C#
  - Multiplayer
  - Horror
  - Procedural Generation
summary: "A thrilling multiplayer horror puzzle game where players race to escape a maze while being hunted by AI monsters."
---


<div class="text-center p-4">
  <img width="700px" class="img-fluid rounded shadow" src="../img/startmenu.png" alt="Into the Shadows Logo">
  <h3 class="mt-3">A thrilling race to the center — with a monster by your side.</h3>
</div>

<nav class="minimal-toc">
  <a href="#game-pitch">Game Pitch</a>
  <a href="#game-trailer">Trailer</a>
  <a href="#game-design--art">Design</a>
  <a href="#whats-next">Roadmap</a>
  <a href="#development-team">Team</a>
  <a href="#technical-details">Tech</a>
</nav>

## Game Pitch

***In The Shadows*** is a fast-paced multiplayer horror puzzle game where players must escape a dark maze while being relentlessly hunted by AI-controlled monsters. Each match pits up to four players against a terrifying AI that won't stop until you're eliminated.

Players choose both a character and a monster partner, each with their own future special abilities and spawn on the edge of a procedurally generated maze. Your goal? Navigate the maze, avoid being hunted, and find the hidden door in the center to escape.

Use strategy and tools like shotguns to distract or slow the monster, but be warned: getting caught a few times means you're out. Fast-paced matches lasting 5–10 minutes make this the perfect game for speedrunners, horror fans, and competitive players alike. Earn gold, unlock new characters, monsters, and prepare for a ranked system and additional upgrades in future updates.

**Will you find the door, or will the shadows find you?**

## Game Trailer

<div class="video-container text-center my-5">
  <div class="embed-responsive embed-responsive-16by9 trailer-wrapper">
    <iframe class="embed-responsive-item rounded shadow" src="https://youtu.be/r3j6km0amA4" allowfullscreen></iframe>
  </div>
  <p class="text-muted mt-3"><em>See our gameplay in action</em></p>
</div>

## Game Design & Art

Preview some of our UI and concept work:

<div class="row">
  <div class="col-md-6">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/gameplay.png" alt="Gameplay Screenshot">
      <p class="text-muted"><em>Gameplay</em></p>
    </div>
  </div>
  <div class="col-md-6">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/startmenu.png" alt="Start Menu">
      <p class="text-muted"><em>Start Menu</em></p>
    </div>
  </div>
</div>

<div class="row">
  <div class="col-md-4">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/character_selection.png" alt="Character Selection">
      <p class="text-muted"><em>Character Selection</em></p>
    </div>
  </div>
  <div class="col-md-4">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/main_menu.png" alt="Main Menu">
      <p class="text-muted"><em>Main Menu</em></p>
    </div>
  </div>
  <div class="col-md-4">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/shop.png" alt="Shop Interface">
      <p class="text-muted"><em>Shop</em></p>
    </div>
  </div>
</div>

## What's Next

Our team is focused on these key improvements for the full release:

<div class="roadmap my-5">
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-users text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>Expanded Online Features</h4>
      <p>Refined matchmaking, lobby chat, and smoother gameplay synchronization.</p>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-ghost text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>New Monsters & Survivors</h4>
      <p>Unique character abilities that enhance strategic depth and replayability.</p>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-bug text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>Polish & Optimization</h4>
      <p>Fixing animation glitches and improving player controls for smoother gameplay.</p>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-sliders-h text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>Accessibility Options</h4>
      <p>Customizable controls, display settings, and audio preferences.</p>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-map text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>Environmental Hazards</h4>
      <p>New maps with fog, traps, and darkness mechanics for unpredictable gameplay.</p>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-icon">
      <i class="fas fa-book text-accent"></i>
    </div>
    <div class="roadmap-content">
      <h4>Story Campaign</h4>
      <p>Mission-based adventures with cutscenes and unlockable lore elements.</p>
    </div>
  </div>
</div>

<style>
.roadmap {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
}

.roadmap-item {
  display: flex;
  align-items: flex-start;
  background: rgba(30, 30, 30, 0.3);
  border-radius: 8px;
  padding: 1.5rem;
  transition: transform 0.2s, box-shadow 0.2s;
}

.roadmap-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.roadmap-icon {
  font-size: 1.5rem;
  margin-right: 1rem;
  color: var(--accent-color, #64ffda);
}

.roadmap-content h4 {
  margin: 0 0 0.5rem;
  font-size: 1.1rem;
  color: var(--accent-color, #64ffda);
}

.roadmap-content p {
  margin: 0;
  font-size: 0.95rem;
  line-height: 1.5;
  color: var(--text-color, #ccd6f6);
}

.text-accent {
  color: var(--accent-color, #64ffda);
}

/* Video trailer styling */
.video-container {
  width: 95%;
  max-width: 1000px;
  margin-left: auto;
  margin-right: auto;
}

.trailer-wrapper {
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}

.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}

.embed-responsive .embed-responsive-item {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

/* Minimal TOC styling */
.minimal-toc {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1.5rem;
  margin: 2rem auto 3rem;
  max-width: 800px;
}

.minimal-toc a {
  color: var(--text-color, #f5f5f5);
  text-decoration: none;
  font-size: 0.95rem;
  position: relative;
  transition: color 0.2s ease;
  padding-bottom: 4px;
}

.minimal-toc a::after {
  content: '';
  position: absolute;
  width: 0;
  height: 1px;
  bottom: 0;
  left: 0;
  background-color: var(--accent-color, #64ffda);
  transition: width 0.3s ease;
}

.minimal-toc a:hover {
  color: var(--accent-color, #64ffda);
}

.minimal-toc a:hover::after {
  width: 100%;
}

@media (max-width: 576px) {
  .minimal-toc {
    gap: 1rem;
  }
  
  .minimal-toc a {
    font-size: 0.85rem;
  }
}
</style>

