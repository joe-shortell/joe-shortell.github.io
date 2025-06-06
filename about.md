---
layout: page
title:
permalink: /about/
---

<div class="profile-container">
  <div class="profile-left">
    <img src="/assets/images/your-photo.jpg" alt="Joe Shortell" class="profile-pic" />
    <h2>Joe Shortell</h2>
    <p>Urban Economist</p>
  </div>

  <div class="profile-right">
    <h2>About me</h2>
    <p>
      I'm an economist, fascinated by cities and interested in understanding how they work, from their development to their decline, or hopefully endurance.
    </p>
    <p>
      I also love food and think about it all the time. In particular, I like to dive deep into the local cuisine, wherever I happen to be at the time, leading to my quest to find the best cheesesteak in Philadelphia.
    </p>

    <h3>Interests</h3>
    <ul>
      <li>Land Use Reform</li>
      <li>Cartography</li>
      <li>Delicious Food</li>
    </ul>

    <h3>Education</h3>
    <p><strong>M.Sc in Applied Economics</strong><br />
    University of Barcelona, 2022</p>
    <p><strong>B.A. in Theoretical Economics</strong><br />
    Trinity University, 2020</p>
  </div>
</div>

<style>
  .profile-container {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 2em;
    margin-top: 1.5em;
  }

  .profile-left {
    flex: 0 0 180px;
    text-align: center;
  }

  .profile-pic {
    width: 120px;
    height: 160px;
    object-fit: cover;
    border-radius: 50% / 50%;
    margin-bottom: 0.75em;
  }


  .profile-left h2 {
    margin: 0.25em 0 0;
    font-size: 1.2em;
  }

  .profile-left p {
    margin: 0;
    font-size: 0.95em;
    color: #666;
  }

  .profile-right {
    flex: 1 1 60%;
    min-width: 280px;
  }

  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column;
      align-items: center;
    }

    .profile-left {
      margin-bottom: 1em;
    }

    .

