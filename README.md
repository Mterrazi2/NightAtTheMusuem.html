<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Night at the Museum | Gameplay Systems</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #0b0c10;
    color: #e6e6e6;
    line-height: 1.7;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 60px 20px;
}

a {
    color: #66c0ff;
    text-decoration: none;
}

a:hover {
    color: white;
}

.back {
    margin-bottom: 40px;
    display: inline-block;
}

.hero {
    margin-bottom: 60px;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 15px;
}

.subtitle {
    color: #9aa0a6;
    margin-bottom: 20px;
}

.video-container {
    margin-top: 30px;
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
}

.video-container iframe {
    position: absolute;
    width: 100%;
    height: 100%;
}

section {
    margin-top: 60px;
}

h2 {
    border-left: 4px solid #66c0ff;
    padding-left: 10px;
    margin-bottom: 20px;
}

ul {
    margin-left: 20px;
    margin-top: 10px;
}

.tech {
    margin-top: 20px;
}

.tech span {
    display: inline-block;
    background-color: #1f2230;
    padding: 6px 10px;
    margin: 5px 5px 0 0;
    border-radius: 4px;
    font-size: 13px;
}

.footer {
    margin-top: 100px;
    text-align: center;
    color: #777;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="container">

<a class="back" href="https://mterrazi2.github.io/">← Back to Portfolio</a>

<div class="hero">
<h1>Night at the Museum</h1>
<div class="subtitle">
First-Person Stealth Game | Unreal Engine | C++
</div>

<p>
A systems-driven stealth experience focused on AI perception, player visibility,
and dynamic alert state transitions. Designed with modular architecture
to allow scalable stealth behaviors and performance-conscious gameplay systems.
</p>

<div class="video-container">
<iframe src="YOUR_YOUTUBE_EMBED_LINK"
frameborder="0"
allowfullscreen>
</iframe>
</div>

<div class="tech">
<span>Unreal Engine</span>
<span>C++</span>
<span>AI Perception</span>
<span>State Machines</span>
<span>Optimization</span>
</div>
</div>

<section>
<h2>Project Overview</h2>
<p>
Night at the Museum is a first-person stealth prototype centered around systemic AI detection
and tension-driven gameplay. The core objective was to build a scalable stealth framework
that could support patrol systems, alert escalation, and player feedback loops.
</p>
</section>

<section>
<h2>Gameplay Systems Implemented</h2>
<ul>
<li>AI Perception-based detection system (sight + awareness thresholds)</li>
<li>Multi-state alert system (Idle, Suspicious, Alerted, Searching)</li>
<li>Player visibility evaluation logic</li>
<li>Modular patrol route behavior</li>
<li>Optimized tick logic to reduce unnecessary processing</li>
</ul>
</section>

<section>
<h2>Technical Challenges</h2>
<p>
One of the primary challenges was ensuring smooth transitions between AI states
without creating erratic behavior. This was solved by implementing controlled
state machine logic and clearly defined transition conditions.
</p>

<p>
Another focus area was performance optimization. AI logic was structured
to minimize unnecessary runtime checks, ensuring stable performance
with multiple active enemies.
</p>
</section>

<section>
<h2>What I Would Improve</h2>
<ul>
<li>Expanded sensory system (sound propagation simulation)</li>
<li>Dynamic difficulty scaling based on player stealth success</li>
<li>Tool-based stealth gadgets with modular interaction systems</li>
</ul>
</section>

<div class="footer">
© 2026 Michael Terrazi
</div>

</div>

</body>
</html>
