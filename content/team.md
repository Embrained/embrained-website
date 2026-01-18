+++
title = "Team"
weight = 4
draft = false
+++

<style>
.team-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 3rem;
  padding: 2rem 0;
}
.team-card {
  width: 100%;
  max-width: 600px;
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 12px;
  padding: 3rem;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.team-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 40px rgba(188, 19, 254, 0.2); /* Neon Purple Glow */
  border-color: #bc13fe;
}
.team-img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1.5rem;
  border: 3px solid rgba(255,255,255,0.1);
  transition: border-color 0.3s ease;
}
.team-card:hover .team-img {
  border-color: #bc13fe;
}
.team-name {
  font-size: 1.8rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
  color: #fff;
}
.team-role {
  display: inline-block;
  background: rgba(188, 19, 254, 0.15);
  color: #bc13fe;
  padding: 0.3rem 1rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  letter-spacing: 1px;
}
.team-bio {
  font-size: 1rem;
  line-height: 1.7;
  color: #ddd;
  margin-bottom: 1.5rem;
}
.team-link {
  display: inline-flex;
  align-items: center;
  color: #fff;
  text-decoration: none;
  border-bottom: 1px dotted rgba(255,255,255,0.5);
  transition: color 0.3s ease;
}
.team-link:hover {
  color: #bc13fe;
  border-bottom-color: #bc13fe;
}
</style>

## 

<div class="team-container">
  <!-- Chris Harris -->
  <div class="team-card">
    <img src="images/ChrisHarris.jpg" alt="Dr. Christopher Harris" class="team-img">
    <div class="team-name">Dr. Christopher Harris</div>
    <div class="team-role">FOUNDER & CEO</div>
    <div class="team-bio">
      A neuroscientist and neuroroboticist who spent a decade exploring biological circuits, intelligent behavior, and conscious experience. Works at the intersection of wetware, software, and hardware as the creator of the SpikerBot platform.
    </div>
    <a href="https://www.youtube.com/watch?v=CbOJHywZ-J0" target="_blank" class="team-link">Watch: SpikerBots Talk</a>
  </div>

  <!-- John Griffiths -->
  <div class="team-card">
    <img src="images/JohnGriffiths.jpg" alt="Dr. John Griffiths" class="team-img">
    <div class="team-name">Dr. John Griffiths</div>
    <div class="team-role">CSO & SPECIAL ADVISOR</div>
    <div class="team-bio">
      Head of the Whole Brain Modelling Group at the Krembil Centre for Neuroinformatics. His research bridges the gap between computational models and biological reality through high-resolution neural dynamics.
    </div>
    <a href="https://www.youtube.com/watch?v=9x6dwdle8WQ" target="_blank" class="team-link">Watch: Whole Brain Modelling</a>
  </div>
</div>
								
