slama 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Oumaima | Growth Marketer</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<style>
:root {
  --dark: #111;
  --gray: #666;
  --light: #f7f7f7;
  --accent: #5b5bf7;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  color: var(--dark);
  background: white;
  line-height: 1.7;
}

/* HEADER */
header {
  padding: 90px 20px;
  text-align: center;
}

header h1 {
  font-family: 'Playfair Display', serif;
  font-size: 48px;
  margin-bottom: 10px;
}

header p {
  font-size: 18px;
  color: var(--gray);
  max-width: 650px;
  margin: auto;
}

/* SECTIONS */
section {
  max-width: 1100px;
  margin: auto;
  padding: 80px 20px;
}

h2 {
  font-family: 'Playfair Display', serif;
  font-size: 34px;
  margin-bottom: 40px;
}

/* STATS */
.stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
}

.stat {
  background: var(--light);
  padding: 35px;
  border-radius: 14px;
}

.stat h3 {
  font-size: 32px;
  margin: 0;
}

.stat p {
  color: var(--gray);
}

/* CASE STUDY */
.case {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px;
  margin-bottom: 80px;
}

.case img {
  width: 100%;
  border-radius: 14px;
  box-shadow: 0 20px 40px rgba(0,0,0,0.08);
}

.case p {
  color: var(--gray);
}

ul {
  padding-left: 18px;
}

li {
  margin-bottom: 8px;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 50px 20px;
  color: var(--gray);
  border-top: 1px solid #eee;
}

@media (max-width: 900px) {
  .case {
    grid-template-columns: 1fr;
  }

  header h1 {
    font-size: 38px;
  }
}
</style>
</head>

<body>

<header>
  <h1>Oumaima</h1>
  <p>
    Growth & Performance Marketer focused on transaction growth and
    organic social media performance through data-driven strategies.
  </p>
</header>

<section>
  <h2>Impact Overview</h2>
  <div class="stats">
    <div class="stat">
      <h3>+70–90%</h3>
      <p>Year-over-year transaction growth</p>
    </div>
    <div class="stat">
      <h3>298K+</h3>
      <p>Total organic video views</p>
    </div>
    <div class="stat">
      <h3>230K+</h3>
      <p>Users reached organically</p>
    </div>
    <div class="stat">
      <h3>+280%</h3>
      <p>Profile visit growth</p>
    </div>
  </div>
</section>

<section>
  <h2>Case Study — Transaction Growth</h2>
  <div class="case">
    <div>
      <p><strong>Goal</strong></p>
      <p>Support sustainable transaction growth through content-led marketing.</p>

      <p><strong>Actions</strong></p>
      <ul>
        <li>Audience-focused messaging</li>
        <li>Localized content strategy</li>
        <li>Clear service communication</li>
      </ul>

      <p><strong>Results</strong></p>
      <ul>
        <li>Consistent month-over-month growth</li>
        <li>Record-high transaction levels</li>
      </ul>
    </div>

    <img src="transactions.png" alt="Transaction growth">
  </div>
</section>

<section>
  <h2>Case Study — TikTok Performance</h2>
  <div class="case">
    <div>
      <p><strong>Goal</strong></p>
      <p>Increase organic reach and engagement without paid ads.</p>

      <p><strong>Actions</strong></p>
      <ul>
        <li>Educational & trend-based videos</li>
        <li>Bilingual content (Arabic & English)</li>
        <li>Consistent posting schedule</li>
      </ul>

      <p><strong>Results</strong></p>
      <ul>
        <li>Multiple videos with 10K–28K views</li>
        <li>Strong organic spikes</li>
      </ul>
    </div>

    <img src="tiktok-performance.png" alt="TikTok performance">
  </div>
</section>

<footer>
  <p>Contact: yourname@email.com · LinkedIn available on request</p>
</footer>

</body>
</html>

