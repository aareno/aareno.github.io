---
layout: project
type: project
image: img/logo2.jpg
title: "Seen"
date: 2025
published: true
labels:
  - Java
  - SQLite
  - XML
  - Android
summary: "A mobile application enabling users to create and manage watchlists for TV shows."
---


<div class="text-center mb-4">
  <img width="700px" class="img-fluid rounded shadow" src="../img/logo2.jpg" alt="Seen App Logo">
  <h3 class="mt-3">Track your shows, one episode at a time.</h3>
</div>

<div class="minimal-nav d-flex justify-content-center flex-wrap my-4">
  <a href="#overview" class="mx-3">Overview</a>
  <a href="#features" class="mx-3">Features</a>
  <a href="#screenshots" class="mx-3">Screenshots</a>
  <a href="#technology" class="mx-3">Technology</a>
  <a href="#development" class="mx-3">Development</a>
</div>

## Overview {#overview}

**Seen** is a minimalist watchlist app designed to help users effortlessly track their favorite anime, K-dramas, and TV shows. With an intuitive interface and comprehensive tracking features, Seen makes it easy to manage what you're currently watching, what you've finished, and what you plan to watch next.

The app provides a centralized platform for maintaining your media consumption across different genres and platforms, giving you clear progress indicators and organized lists to ensure you never lose track of your shows again.

## Features {#features}

<div class="features-row">
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-tasks text-accent"></i>
    </div>
    <h4>Progress Tracking</h4>
    <p>Visual progress bars show exactly how far you are in each series.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-list text-accent"></i>
    </div>
    <h4>Multiple Lists</h4>
    <p>Organize content into "Watching" and "Watched" categories.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-search text-accent"></i>
    </div>
    <h4>Advanced Search</h4>
    <p>Find shows quickly with external API integration.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-sliders-h text-accent"></i>
    </div>
    <h4>Customizable UI</h4>
    <p>Enable or disable tabs based on your preferences.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-shield-alt text-accent"></i>
    </div>
    <h4>Content Filtering</h4>
    <p>Age-appropriate content controls for your comfort.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-feather text-accent"></i>
    </div>
    <h4>Minimal Design</h4>
    <p>Clean, distraction-free interface for better focus.</p>
  </div>
</div>

## Screenshots {#screenshots}

<div class="carousel-container my-5">
  <div id="animeCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#animeCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#animeCarousel" data-slide-to="1"></li>
      <li data-target="#animeCarousel" data-slide-to="2"></li>
      <li data-target="#animeCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Slides -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <div class="d-flex justify-content-center flex-column align-items-center">
          <div class="carousel-image-container mb-2">
            <img class="img-fluid rounded shadow" src="../img/animescreen.png" alt="My Anime List">
          </div>
          <div class="carousel-caption-below text-center">
            <h5>Watching List</h5>
            <p>Keep track of shows you're currently watching</p>
          </div>
        </div>
      </div>
      
      <div class="carousel-item">
        <div class="d-flex justify-content-center flex-column align-items-center">
          <div class="carousel-image-container mb-2">
            <img class="img-fluid rounded shadow" src="../img/searchscreen2.png" alt="Popular Anime">
          </div>
          <div class="carousel-caption-below text-center">
            <h5>Popular Anime</h5>
            <p>Discover trending shows in the anime community</p>
          </div>
        </div>
      </div>
      
      <div class="carousel-item">
        <div class="d-flex justify-content-center flex-column align-items-center">
          <div class="carousel-image-container mb-2">
            <img class="img-fluid rounded shadow" src="../img/searchscreen.png" alt="K-Drama Collection">
          </div>
          <div class="carousel-caption-below text-center">
            <h5>K-Drama Collection</h5>
            <p>Browse your favorite Korean dramas</p>
          </div>
        </div>
      </div>
      
      <div class="carousel-item">
        <div class="d-flex justify-content-center flex-column align-items-center">
          <div class="carousel-image-container mb-2">
            <img class="img-fluid rounded shadow" src="../img/settingsscreen.png" alt="Settings Screen">
          </div>
          <div class="carousel-caption-below text-center">
            <h5>Settings Screen</h5>
            <p>Customize your Content</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Controls -->
    <a class="carousel-control-prev" href="#animeCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#animeCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
  
  <div class="text-center mt-3">
    <p class="text-muted"><em>Click through to explore different categories in your collection</em></p>
  </div>
</div>

## Technology {#technology}

<div class="tech-stack d-flex flex-wrap justify-content-center my-5">
  <div class="tech-item mx-3 my-2 text-center">
    <i class="fab fa-java fa-2x mb-2 text-accent"></i>
    <div>Java</div>
  </div>
  <div class="tech-item mx-3 my-2 text-center">
    <i class="fas fa-database fa-2x mb-2 text-accent"></i>
    <div>SQLite</div>
  </div>
  <div class="tech-item mx-3 my-2 text-center">
    <i class="fas fa-code fa-2x mb-2 text-accent"></i>
    <div>XML</div>
  </div>
  <div class="tech-item mx-3 my-2 text-center">
    <i class="fab fa-android fa-2x mb-2 text-accent"></i>
    <div>Android SDK</div>
  </div>
</div>

## Development {#development}

Seen was developed with a focus on simplicity and efficiency. Key development principles included:

- **Clean architecture** separating UI, business logic, and data storage
- **Room database** implementation for robust data persistence
- **Repository pattern** abstracting data sources and providing a clean API for the application
- **API integration** with popular services like TVMaze, OmDB and MyAnimeList for comprehensive show information
- **Adaptive UI** that works well on different screen sizes and device orientations

### Future Roadmap

The app continues to evolve with planned features including:

- User accounts and cloud synchronization for multi-device usage
- Social features for sharing and recommending shows to friends
- Enhanced analytics showing viewing habits and preferences
- Integration with streaming services to launch shows directly

The app was created as a personal project to solve my own challenge of keeping track of multiple shows across different streaming platforms. It evolved into a comprehensive solution that others with similar needs could benefit from as well.

<style>
.minimal-nav a {
  color: var(--text-color, #f5f5f5);
  text-decoration: none;
  position: relative;
  padding-bottom: 0.25rem;
  transition: color 0.2s ease;
}

.minimal-nav a::after {
  content: '';
  position: absolute;
  width: 0;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: var(--accent-color, #64ffda);
  transition: width 0.3s ease;
}

.minimal-nav a:hover {
  color: var(--accent-color, #64ffda);
}

.minimal-nav a:hover::after {
  width: 100%;
}

/* Replace the grid layout with a flex layout for features */
.features-grid {
  display: none; /* Hide the original grid layout */
}

.features-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 1rem;
  margin: 3rem 0;
}

.feature-card {
  flex: 1 1 13%;
  min-width: 150px;
  background: rgba(30, 30, 30, 0.2);
  padding: 1rem;
  border-radius: 8px;
  transition: transform 0.2s, box-shadow 0.2s;
  text-align: center;
  margin-bottom: 1rem;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.feature-card h4 {
  font-size: 1rem;
  margin-bottom: 0.5rem;
  color: var(--accent-color, #64ffda);
}

.feature-card p {
  font-size: 0.9rem;
  line-height: 1.3;
}

.feature-icon {
  font-size: 1.75rem;
  margin-bottom: 0.75rem;
  color: var(--accent-color, #64ffda);
}

.text-accent {
  color: var(--accent-color, #64ffda);
}

.tech-item {
  width: 100px;
}

.carousel-image-container {
  width: 280px; /* Control width for vertical phone screenshots */
  overflow: hidden;
}

.carousel-caption-below {
  width: 280px;
  padding: 10px;
  margin-top: 10px;
}

.carousel-caption-below h5 {
  color: var(--accent-color, #64ffda);
  margin-bottom: 5px;
}

.carousel-caption-below p {
  color: var(--text-color, #f5f5f5);
  font-size: 0.9rem;
}

/* Override Bootstrap's default caption positioning */
.carousel-caption {
  display: none;
}
</style>

<script>
  // Initialize the carousel when the page is loaded
  document.addEventListener('DOMContentLoaded', function() {
    // Check if jQuery is available (Bootstrap carousel depends on jQuery)
    if (typeof jQuery !== 'undefined') {
      // Initialize the carousel with jQuery
      $('#animeCarousel').carousel({
        interval: 5000, // Change slide every 5 seconds
        wrap: true      // Cycle continuously
      });
      
      // Add click handlers for manual navigation
      $('.carousel-control-prev').click(function() {
        $('#animeCarousel').carousel('prev');
        return false;
      });
      
      $('.carousel-control-next').click(function() {
        $('#animeCarousel').carousel('next');
        return false;
      });
      
      // Enable indicator clicks
      $('.carousel-indicators li').click(function() {
        $('#animeCarousel').carousel($(this).data('slide-to'));
      });
    } else {
      // Fallback for when jQuery is not available
      console.log('jQuery not found. Carousel may not function properly.');
      
      // Basic vanilla JS carousel implementation
      const carousel = document.getElementById('animeCarousel');
      const items = carousel.querySelectorAll('.carousel-item');
      const prevBtn = carousel.querySelector('.carousel-control-prev');
      const nextBtn = carousel.querySelector('.carousel-control-next');
      const indicators = carousel.querySelectorAll('.carousel-indicators li');
      let currentIndex = 0;
      
      function showSlide(index) {
        // Hide all slides
        items.forEach(item => item.classList.remove('active'));
        // Show the selected slide
        items[index].classList.add('active');
        // Update indicators
        indicators.forEach(indicator => indicator.classList.remove('active'));
        indicators[index].classList.add('active');
        currentIndex = index;
      }
      
      prevBtn.addEventListener('click', function(e) {
        e.preventDefault();
        currentIndex = (currentIndex > 0) ? currentIndex - 1 : items.length - 1;
        showSlide(currentIndex);
      });
      
      nextBtn.addEventListener('click', function(e) {
        e.preventDefault();
        currentIndex = (currentIndex < items.length - 1) ? currentIndex + 1 : 0;
        showSlide(currentIndex);
      });
      
      indicators.forEach((indicator, index) => {
        indicator.addEventListener('click', function() {
          showSlide(index);
        });
      });
    }
  });
</script>

