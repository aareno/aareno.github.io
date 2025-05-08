---
layout: project
type: project
image: img/cabletrack.png
title: "CableTrack.Pro"
date: 2023
published: true
labels:
  - Javascript
  - React
  - MongoDB
  - Meteor
  - Software Engineering
summary: "A web application that helps electricians quickly and easily create schedules for their projects."
---

# CableTrack.Pro

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Screenshots](#screenshots)
- [Development Process](#development-process)
- [My Contributions](#my-contributions)
- [Technical Implementation](#technical-implementation)
- [Lessons Learned](#lessons-learned)
- [Team](#team)

## Overview

[CableTrack.Pro](https://ingeniouspartners.github.io/cabletrack.pro/) is a specialized tool designed to streamline project management for electricians. The application enables efficient tracking of cable meta-data, pull-ins, terminations, and testing procedures. By centralizing this information, electricians can generate Building Information Management (BIM) reports and exports with minimal effort, significantly improving workflow efficiency.

<div class="text-center p-4">
  <img width="600px" class="img-fluid rounded shadow" src="../img/home page.png" alt="CableTrack.Pro Homepage">
  <p class="text-muted"><em>CableTrack.Pro homepage showing the main dashboard interface</em></p>
</div>

## Key Features

- **Project Management**: Create, edit, view, and delete electrical projects
- **Cable Tracking**: Document and organize cable specifications and metadata
- **Installation Monitoring**: Track pull-in progress and termination status
- **Testing Documentation**: Record and verify testing procedures and results
- **Report Generation**: Export BIM-compatible reports for project documentation

## Screenshots

<div class="row">
  <div class="col-sm-6">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/list project.png" alt="Projects Page">
      <p class="text-muted"><em>Projects dashboard showing active electrical projects</em></p>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="text-center p-3">
      <img width="100%" class="img-fluid rounded shadow" src="../img/view projects.png" alt="Project Details">
      <p class="text-muted"><em>Detailed view of an individual project's specifications</em></p>
    </div>
  </div>
</div>

## Development Process

This application was developed using the **Model-View-Design (MVD)** pattern to separate business logic from the user interface. We implemented an issue-driven project management approach to track progress and ensure accountability throughout the development cycle.

### Technologies Used

- **Frontend**: React.js, Bootstrap
- **Backend**: Meteor.js
- **Database**: MongoDB
- **Testing**: TestCafe
- **Deployment**: GitHub Pages

## My Contributions

As a software engineer on the [Indigenous Partners](https://github.com/ingeniouspartners) team, I focused on implementing the project management functionality:

- **Project Creation**: Designed and implemented the "Add Project" interface
- **Project Management**: Built edit, view, list, and delete capabilities
- **Data Validation**: Implemented validation logic for project form inputs
- **Testing**: Created TestCafe test suites for the Projects component
- **Documentation**: Contributed to technical documentation and user guides

## Technical Implementation

The project management module follows a structured architecture:

```javascript
// Project Schema Example
const ProjectSchema = new SimpleSchema({
  name: {
    type: String,
    required: true,
    max: 50,
  },
  description: {
    type: String,
    required: true,
    max: 200,
  },
  startDate: {
    type: Date,
    required: true,
  },
  estimatedCompletion: {
    type: Date,
    required: true,
  },
  // Additional fields...
});
```

## Lessons Learned

### Technical Growth
Working on CableTrack.Pro enhanced my skills with:
- **Meteor.js ecosystem**: Gained practical experience with reactive data and publications
- **MongoDB integration**: Learned efficient database schema design and query optimization
- **Deployment processes**: Mastered continuous integration workflows

### Teamwork & Collaboration
This project was my first team-based coding experience, where I discovered the critical importance of:

- **Communication**: Regular sync-ups and code reviews kept everyone aligned
- **Adaptability**: Learning to merge code and resolve conflicts efficiently
- **Patience**: Working through complex issues without getting frustrated

### Software Engineering Principles
I gained practical understanding of:
- **Design Patterns**: Applied MVD to create maintainable, modular code
- **Issue-Driven Project Management**: Used GitHub issues to track tasks and progress
- **Code Quality**: Implemented consistent styling and documentation practices

## Team

CableTrack.Pro was developed by Indigenous Partners:
- Andrea Jans
- Ursula Nichols
- Matthew Yamamoto
- Mikhail Shkaralevich
- [Your Name]

<div class="text-center p-4">
  <a href="https://github.com/ingeniouspartners" class="btn btn-primary">
    <i class="fab fa-github"></i> View on GitHub
  </a>
  <a href="https://ingeniouspartners.github.io/cabletrack.pro/" class="btn btn-success">
    <i class="fas fa-external-link-alt"></i> Live Demo
  </a>
</div>