---
layout: default
title: "Salado Youth Football & Cheer"
---

<header>
  <h1>Built to Lead. Trained to Win.</h1>
  <p>Salado Youth Football & Cheer isn’t just a program — it’s a mindset.</p>
  <div class="cta">
    <a href="#">Register Now</a>
    <a href="#">Donate</a>
  </div>
</header>

<section>
  <h2 style="text-align: center;">Programs We Offer</h2>
  <div class="cards">
    <div class="card">
      <h3>Flag Football</h3>
      <p>Ages 5–7. Learn fundamentals, teamwork, and confidence.</p>
    </div>
    <div class="card">
      <h3>Tackle Football</h3>
      <p>Ages 8–12. Discipline, drive, and skill-building for life.</p>
    </div>
    <div class="card">
      <h3>Cheer</h3>
      <p>Open to all youth. Spirit, strength, and high-energy team culture.</p>
    </div>
  </div>
</section>

<section>
  <h2 style="text-align: center;">Community. Culture. Champions.</h2>
  <p style="max-width: 700px; margin: 0 auto; text-align: center;">
    This is Salado. Our town. Our kids. Our legacy. Through competition, we build character. 
    Through teamwork, we build leaders. Join us.
  </p>
</section>

<section>
  <h2 style="text-align: center;">Latest News</h2>
  <ul>
    {% for post in site.posts %}
      <li><strong>{{ post.title }}</strong> - {{ post.date | date: "%b %d, %Y" }}</li>
    {% endfor %}
  </ul>
</section>
