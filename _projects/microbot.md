---
layout: post
title: MicroBot - Two Wheel RC Robot
description: MicroBot is a two-wheel differential drive robot that is controlled by the built-in accelerometer on the Micro:bit. 
category: Hardware Development
image: /assets/images/microbot.jpeg
skill: Embed System
---

<div class="project-content">
  <div class="project-header">
    <div class="project-image">
      <img src="/assets/images/microbot.jpeg" alt="Microbot Cover Photo">
    </div>

    <div class="project-intro">
      <div class="focus-area">
        <h2>Focus Areas</h2>
        <div class="tags">
          <span>Embed Software Design</span>
        </div>
      </div>

      <div class="details-grid">

        <div class="description">
          <h2>Description</h2>
          <p>MicroBot is a two-wheel differential drive robot that is controlled by the built-in accelerometer on the Micro:bit. The MicroBot will communicate with other microbots which use a joystick to control the direction and the speed of the wheel on the robot. The joystick controller will use the built-in LEDs matrix that will light up as an arrow in the direction of the joystick and will control the moto velocity. 
          </p>
          <p><strong>Class:</strong> <a href="https://www.mccormick.northwestern.edu/computer-science/academics/courses/descriptions/346.html" target="_blank">COMP_SCI 346: Microcontroller System Design</a></p>
          <p><strong>Team:</strong> 4 Members</p>
          <p><strong>Project Teamline</strong>25 November 2024 - 12 December 2024</p>
        </div>

        <div class="my-role">
          <h2>My Role</h2>
          <p>
          I am responsible for working on the wireless communication for the joystick to send information for the robot to receive using the built-in 2.4GHz radio module from the microbit. I also help work on the motor control using h-bridge. 
          </p>
        </div>
        
      </div>
    </div>
  </div>

  <div class="project-body">

    

    <div class="problem">
      <h2>Problem</h2>
      <p>Develop an interactive application utilizing Microbit that incorporates at least two sensors and one output mechanism to address a practical or creative challenge. The project should align with a $40 per team member budget, encouraging innovation and teamwork while leveraging Microbit's capabilities for hands-on learning and real-world applications.
      </p>
    </div>

    <div class="solution">
      <h2>Solution</h2>
      <p>We designed a two-wheel differential drive robot controlled by the accelerometer on a Micro:bit. Tilting one Micro:bit adjusts the robot’s speed and direction, communicated wirelessly to another Micro:bit on the robot. An ultrasonic sensor detects obstacles, triggering warning vibrations and sound alerts when thresholds are reached. The robot’s LED matrix displays directional arrows corresponding to motor velocity. This project integrates multiple peripherals, wireless communication, and features like PID control, audio output, and accelerometer readings, leveraging skills gained in weekly labs. The robot’s design emphasizes modularity, interactivity, and safety for a seamless user experience.

</p>
    </div>
    <div class="impact">
          <h2>Result</h2>
          <video width="1560" height="760" controls>
          <source src="/assets/videos/microbot_demo.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
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
    background-color: #f48023;
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
