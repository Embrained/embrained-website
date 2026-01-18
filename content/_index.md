---
title: ""
description: |
  <style>
    /* Suppress theme defaults */
    #header h1, .header h1, .logo { display: none !important; }

    .content-center {
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* 1. STATUS BADGE (Top) */
    .status-container {
      display: flex;
      justify-content: center;
      margin-top: -60px; /* Adjust this to move closer to the line */
      margin-bottom: 20px;
    }

    .status-link {
      display: inline-flex;
      align-items: center;
      text-decoration: none !important;
      border: 1px solid #333 !important;
      padding: 6px 16px;
      border-radius: 20px;
      font-size: 0.7rem;
      color: #888888 !important;
      background: rgba(0,0,0,0.5);
      transition: all 0.3s ease; /* Smooth transition for the 'pop' */
    }

    .status-link:hover {
      transform: translateY(-3px); /* The 'Pop Up' effect */
      border-color: #00ff41 !important;
      color: #ffffff !important;
      box-shadow: 0 4px 15px rgba(0, 255, 65, 0.2);
    }

    /* 2. SOCIAL ICONS (Below Status) */
    .social-container {
      margin-bottom: 40px;
      display: flex;
      justify-content: center;
      gap: 45px;
      align-items: center;
    }

    .social-icon {
      display: inline-block;
      text-decoration: none !important;
      border: none !important;
      transition: all 0.3s ease; /* Ensures the icon pops smoothly */
    }

    .social-icon:hover {
      transform: scale(1.2) translateY(-5px); /* Scales up and moves up */
      filter: drop-shadow(0 0 8px rgba(255, 255, 255, 0.5));
    }

    .social-icon svg { fill: white; width: 26px; height: 26px; display: block; }
    .social-icon img { display: block; width: 26px; height: 26px; }

    /* 3. BRAND SECTION (Bottom - Pushed down to show BG image) */
    .brand-section {
      margin-top: 280px; /* Increase or decrease to frame your image focal point */
    }

    .brand-title {
      font-size: 1.2rem;
      font-weight: 700;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: #ffffff;
      margin-bottom: 0.5rem;
      display: block;
      font-family: -apple-system, sans-serif;
    }

    .tagline {
      font-size: 0.85rem;
      color: #ffffff;
      opacity: 0.95;
      font-family: monospace;
      display: block;
      letter-spacing: 0.1em;
    }

    .status-dot {
      width: 6px; height: 6px;
      background-color: #00ff41;
      border-radius: 50%;
      margin-right: 10px;
      box-shadow: 0 0 5px #00ff41;
    }


   /* Widens the subpage modal boxes */
   #main article {
    width: 80rem !important;      /* Increase this value to make it wider */
    max-width: 90% !important;   /* Ensures it doesn't break on smaller screens */
   }

   /* Optional: Adjust the content inside to breathe better */
   #main article > * {
    padding-left: 2rem;
    padding-right: 2rem;
   }

  </style>

  <div class="content-center">
    <div class="status-container">
      <a href="." class="status-link">
        <span class="status-dot"></span>
        SYSTEM STATUS: OPERATIONAL / STEALTH
      </a>
    </div>

    <div class="social-container">
      <a href="https://www.linkedin.com/company/110520989" class="social-icon">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
      </a>
      <a href="https://bsky.app/profile/embrained.ai" class="social-icon">
        <img src="https://cdn.simpleicons.org/bluesky/white" alt="BlueSky">
      </a>
      <a href="https://x.com/embrainedai" class="social-icon">
        <img src="https://cdn.simpleicons.org/x/white" alt="X">
      </a> 
      <a href="https://github.com/embrained" class="social-icon">
        <img src="https://cdn.simpleicons.org/github/white" alt="GitHub">
      </a>
    </div>

    <div class="brand-section">
      <span class="brand-title">EMBRAINED, LLC</span>
      <span class="tagline"> Disaggregated Embodied Intelligence</span>
    </div>
  </div>
---


