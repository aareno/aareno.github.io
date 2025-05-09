---
layout: project
type: project
image: img/ics.png
title: "Identifier Name IDE Plugin"
date: 2025
published: true
labels:
  - Java
  - Kotlin
  - Gradle
  - IntelliJ Platform
  - Static Analysis
summary: "An IntelliJ platform plugin that visually organizes and analyzes code identifiers to improve code quality and navigation."
---

<div class="text-center p-4">
  <img width="700px" class="img-fluid rounded shadow" src="../img/ics.png" alt="Identifier Name IDE Plugin">
  <h3 class="mt-3">Improving code quality through identifier analysis</h3>
</div>

<nav class="minimal-nav">
  <a href="#overview">Overview</a>
  <a href="#features">Features</a>
  <a href="#methodology">Methodology</a>
  <a href="#challenges">Challenges</a>
  <a href="#tools">Tools</a>
  <a href="#team">Team</a>
</nav>

## Overview

The Identifier Name IDE Plugin enhances code quality by analyzing how developers name variables, methods, and classes within their software projects. Identifiers contribute approximately 70% of source code and serve as critical documentation that conveys developer intent. The plugin provides visualization tools for identifier naming patterns, detects naming violations, and suggests improvements, enabling developers to maintain consistent coding standards and improve code readability.

## Features

<div class="features-grid">
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-chart-bubble text-accent"></i>
    </div>
    <h4>Bubble Chart Visualization</h4>
    <p>Displays an interactive bubble chart that highlights identifier naming patterns, organized by categories of identifiers. Each bubble corresponds to a specific set of identifiers, with tooltips that provide more details about the set.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-exclamation-triangle text-accent"></i>
    </div>
    <h4>Violations Detection</h4>
    <p>Creates an identifier report that highlights identifier naming violations detected across the project along with a rating of violations on a scale of severity. Users can view which identifiers have violations and suggestions on how to resolve them.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-file-export text-accent"></i>
    </div>
    <h4>Data Export</h4>
    <p>Developed an export system that allows users to download identifier data in CSV or JSON formats. This helps support easy sharing, analysis, and documentation of identifier usage and violations.</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">
      <i class="fas fa-code text-accent"></i>
    </div>
    <h4>Format Identifiers</h4>
    <p>Built a featured system that extracts all identifiers from a project, grouped by their format type (parameters, fields, variables, classes, types).</p>
  </div>
</div>

## Implementation

<div class="row">
  <div class="col-md-6">
    <div class="text-center p-3">
      <img width="105%" class="img-fluid rounded shadow" src="../img/ide3.png" alt="Plugin Interface">
      <p class="text-muted"><em>Data Export Interface</em></p>
    </div>
  </div>
  <div class="col-md-6">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/ide2.png" alt="Violations Panel">
      <p class="text-muted"><em>Violations Detection Panel</em></p>
    </div>
  </div>
</div>

<div class="row">
  <div class="col-md-12">
    <div class="text-center p-3">
      <img width="50%" class="img-fluid rounded shadow" src="../img/ide.png" alt="Data Export View">
      <p class="text-muted"><em>Bubble Chart Visualization</em></p>
    </div>
  </div>
</div>

## Methodology

<div class="methodology-container">
  <div class="methodology-step">
    <span class="step-number">1</span>
    <p>Identifiers are Organized into distinct categories</p>
  </div>
  <div class="methodology-step">
    <span class="step-number">2</span>
    <p>Identifiers are Diagrammed into lists by relationship (Parameter, Field, Variable)</p>
  </div>
  <div class="methodology-step">
    <span class="step-number">3</span>
    <p>Identifiers are Diagrammed into lists by category (Class, Type and Name)</p>
  </div>
  <div class="methodology-step">
    <span class="step-number">4</span>
    <p>Violations are presented with a severity scale</p>
  </div>
  <div class="methodology-step">
    <span class="step-number">5</span>
    <p>Violations are gathered with a zero-to-full that shows the violations</p>
  </div>
  <div class="methodology-step">
    <span class="step-number">6</span>
    <p>Identifiers are evaluated by Type, Class and Name</p>
  </div>
</div>

## Challenges

There were a variety of challenges that were encountered throughout the development of the plugin, particularly with implementing the tool across different coding styles and understanding the framework. Additionally, managing overlapping elements in bubble visualizations and handling the UI responsive involved complex design and event handling aspects. The project also introduced additional layers of testing and debugging.

## Next Steps

The Identifier Name IDE Plugin brings identifier analysis and visualization into the development workflow, aiding in code comprehension and refactoring. Future development will focus on integration with more language-specific conventions, multi-language support for different syntaxes, and more customizations on style preferences to better adapt to the needs of the user.

## Team

<div class="team-section">
  <p><strong>Aaren Orquia, Samuel Yang, Josiah Liu</strong></p>
  <p>Sponsor: Anthony Peruma</p>
  <p>ICS 414 Software Project – Spring 2023</p>
</div>

## Tools & Frameworks

<div class="tools-container">
  <div class="tool-item">
    <img src="https://resources.jetbrains.com/storage/products/intellij-idea/img/meta/intellij-idea_logo_300x300.png" alt="IntelliJ" width="40">
    <span>IntelliJ</span>
  </div>
  <div class="tool-item">
    <img src="https://kotlinlang.org/assets/images/favicon.svg" alt="Kotlin" width="40">
    <span>Kotlin</span>
  </div>
  <div class="tool-item">
    <img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" alt="Java" width="40">
    <span>Java</span>
  </div>
  <div class="tool-item">
    <img src="https://gradle.org/images/gradle-knowledge-graph-logo.png" alt="Gradle" width="40">
    <span>Gradle</span>
  </div>
  <div class="tool-item">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" width="40">
    <span>GitHub</span>
  </div>
</div>

<style>
/* Minimal Navigation */
.minimal-nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1.5rem;
  margin: 2rem auto;
}

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

/* Features Grid */
.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.feature-card {
  background: rgba(30, 30, 30, 0.2);
  padding: 1.5rem;
  border-radius: 8px;
  transition: transform 0.2s, box-shadow 0.2s;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.feature-icon {
  font-size: 1.75rem;
  margin-bottom: 1rem;
  color: var(--accent-color, #64ffda);
}

.feature-card h4 {
  margin-bottom: 1rem;
  color: var(--accent-color, #64ffda);
}

/* Methodology */
.methodology-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.methodology-step {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
}

.step-number {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background-color: var(--accent-color, #64ffda);
  color: var(--bg-color, #0a192f);
  font-weight: bold;
}

/* Team Section */
.team-section {
  background: rgba(30, 30, 30, 0.2);
  padding: 1.5rem;
  border-radius: 8px;
  text-align: center;
  margin: 2rem 0;
}

/* Tools */
.tools-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin: 2rem 0;
}

.tool-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.5rem;
}

.text-accent {
  color: var(--accent-color, #64ffda);
}

@media (max-width: 768px) {
  .minimal-nav {
    gap: 1rem;
  }
  
  .features-grid {
    grid-template-columns: 1fr;
  }
  
  .methodology-container {
    grid-template-columns: 1fr;
  }
}
</style>

