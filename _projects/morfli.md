---
layout: post
title: Morfli
description: A digital "textbook" for introductory materials science that uses computational models to explore materials phenomena.
category: Software Development
image: /assets/images/morfli.jpg
---

<div class="project-content">
  <div class="project-header">
    <div class="project-image">
      <img src="/assets/images/morfli.png" alt="Morfli">
    </div>

    <div class="project-intro">
      <div class="focus-area">
        <h2>Focus Areas</h2>

        <div class="tags">
          <span>UI/UX</span>
          <span>Full Stack Development</span>
          <span>Backend Development</span>
          <span>Frontend Development</span>
        </div>
      </div>

      <div class="details-grid">

        <div class="description">
          <h2>Description</h2>
          <p>
            This project involved designing and developing a flashcard interface for Morfli, an online learning platform. The goal was to provide students with an integrated tool for spaced repetition learning directly within their course materials.
          </p>
          <p><strong>Website:</strong> <a href="https://www.morfli.com/" target="_blank">https://www.morfli.com/</a></p>
          <p><strong>Project Timeline:</strong> September 2023 - April 2024</p>
        </div>        
      </div>
    </div>
  </div>

  <div class="project-body">
      <div class="my-role">
        <h2>My Role</h2>
          <p>I designed and developed Morfli's flashcard interface to enhance learning and retention, conducting user research with students and faculty to gather insights. Using their feedback, I created and refined mockups, then implemented a cohesive and engaging solution. 
          </p>
        </div>

    <div class="problem">
      <h2>Problem</h2>
      <p>Students using Morfli were relying on external flashcard platforms to supplement their learning, which was time-consuming and disruptive to their workflow. These external platforms were also not tailored to specific course content.
      </p>
    </div>

    <div class="solution">
      <h2>Solution</h2>
      <p>A new flashcard block was developed and integrated into the Morfli platform. The solution includes:</p>
      <ul>
        <li>Customizable Flashcard Decks: Instructors can create flashcard decks tailored to their course content.</li>
        <li>Spaced Repetition Integration: The Orbit framework is used to manage spaced repetition schedules and send reminder emails to students.
</li>
        <li>Seamless Integration: The flashcard interface is embedded within Morfi lesson pages, creating a smooth learning experience.
</li>
        <li>User-Friendly Interface: The interface allows instructors to easily create, edit, and manage flashcards, while students can efficiently review and learn from them.
</li>
      </ul>
    </div>
    <div class="impact">
          <h2>Impact</h2>
          <p>The flashcard interface improves student learning efficiency and effectiveness by reducing reliance on external flashcard platforms like Anki or Quizlet, Integrating spaced repetition techniques directly into Morfli, so educators can easily create flashcards inside the lesson page.  This created a more streamlined and less disruptive learning flow for students.
          </p>
        </div>
  </div>
</div>

<style>
  .project-content {
    margin: 0 auto;
    padding: 0 20px;
  }

  .project-header {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;
    margin-bottom: 2rem;
  }

  .project-image img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 1rem;
  }

  .project-intro {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }

  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tags span {
    background-color: #f0f0f0;
    padding: 4px 8px;
    border-radius: 5px;
    font-size: 0.9rem;
  }

  .details-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }

  .details-grid > div {
    margin-bottom: 1.5rem;
  }

  @media (min-width: 768px) {
    .project-header {
      grid-template-columns: 1fr 1fr;
      align-items: start;
    }

    .details-grid {
      grid-template-columns: 1fr 1fr;
    }
  }
</style>
