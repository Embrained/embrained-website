+++
title = "Ecosystem"
weight = 2
draft = false
+++

<style>
  .eco-container {
    display: flex;
    flex-direction: column;
    gap: 3rem;
  }
  .eco-row {
    display: flex;
    align-items: center;
    gap: 2rem;
  }
  .eco-row.reverse {
    flex-direction: row-reverse;
  }
  .eco-image {
    flex: 1.5; /* Increased from 1 to 1.5 to make images larger */
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .eco-image img {
    width: 100%; /* Ensure it takes available space */
    max-width: 100%;
    border-radius: 4px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
  }
  .eco-image img:hover {
    transform: scale(1.05); /* Slight zoom on hover */
    box-shadow: 0 0 20px rgba(188, 19, 254, 0.4); /* Neon Purple Glow */
    border-color: #bc13fe;
  }
  .eco-text {
    flex: 1;
    text-align: left;
  }
  .eco-text h4 {
    margin-bottom: 0.5rem;
    font-size: 1.3rem;
    font-weight: 700;
    letter-spacing: 0.1em;
  }
  .eco-centered {
    text-align: center;
    padding: 2rem;
    background: rgba(255,255,255,0.05);
    border-radius: 8px;
  }
  
  @media (max-width: 768px) {
    .eco-row, .eco-row.reverse {
      flex-direction: column;
      text-align: center;
    }
    .eco-text {
      text-align: center;
    }
  }
</style>

<div class="eco-container">

  <!-- NIMBAR: Image Left -->
  <div class="eco-row">
    <div class="eco-image">
      <img src="images/nimbar_sketch-rmbg.png" alt="Nimbar Software Interface">
    </div>
    <div class="eco-text">
      <h4>NIMBAR</h4>
      <p>A desktop application that acts as the central nervous system, running heavy AI models for navigation and reasoning on your local computer.</p>
    </div>
  </div>

  <!-- PLEXUS: Image Right -->
  <div class="eco-row reverse">
    <div class="eco-image">
      <img src="images/plexus_sketch-rmbg.png" alt="Plexus Hardware Device">
    </div>
    <div class="eco-text">
      <h4>PLEXUS</h4>
      <p>Our proprietary hardware module that handles vision, communication, and immediate safety reflexes for mobile agents.</p>
    </div>
  </div>

  <!-- THE BODY: Centered Text -->
  <div class="eco-row">
    <div class="eco-image">
      <img src="images/body-rmbg.png" alt="Body">
    </div>
    <div class="eco-text">
      <h4>THE BODY</h4>
      <p>Because we focus on intelligence, we do not manufacture wheels. We require our users to build their mobile agents using specific, high-torque third-party chassis (such as the Waveshare Wave Rover) to ensure robust performance.</p>
    </div>
  </div>

  <!-- CARTESO: Image Left -->
  <div class="eco-row">
    <div class="eco-image">
      <img src="images/carteso_sketch-rmbg.png" alt="Carteso Tracking Module">
    </div>
    <div class="eco-text">
      <h4>CARTESO</h4>
      <p style="margin-bottom: 0;">A low-cost, stationary sensory module that connects via USB. It serves as a distinct, accessible entry point, allowing users to experiment with embodied AI and the Nimbar app without the need for a mobile chassis.</p>
    </div>
  </div>

</div>
