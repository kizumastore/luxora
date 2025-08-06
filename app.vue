<template>
<div class="bg-wrap">
  <div class="container">
    <h1 class="title">KIZUMASTORE</h1>
    <h2 class="subtitle">AMAN DAN TERPERCAYA</h2>

    <!-- Pet Catalog -->
    <div class="pet-grid">
      <div class="pet-card">
        <img src="https://raw.githubusercontent.com/kizumastore/luxora/refs/heads/main/public/CorruptedKitsune.webp" alt="Corrupted Kitsune" />
        <h4>Corrupted Kitsune</h4>
        <p>Rp 15.000</p>
      </div>
      <div class="pet-card">
        <img src="https://raw.githubusercontent.com/kizumastore/luxora/refs/heads/main/public/DragonflyIcon.webp" alt="Raiju" />
        <h4>Dragon fly</h4>
        <p>Rp 12.000</p>
      </div>
      <div class="pet-card">
        <img src="public/11111.png" />
        <h4>Mimic</h4>
        <p>Rp 10.000</p>
      </div>
    </div>
  </div>
</div>
</template>

<style>
.bg-wrap {
background: linear-gradient(-45deg, #12001d, #25003e, #1f002b, #32004a);
background-size: 400% 400%;
animation: gradientMotion 12s ease infinite;
min-height: 100vh;
width: 100%;
}

@keyframes gradientMotion {
0% {
  background-position: 0% 50%;
}
50% {
  background-position: 100% 50%;
}
100% {
  background-position: 0% 50%;
}
}

body {
margin: 0;
font-family: 'Segoe UI', sans-serif;
color: white;
overflow-x: hidden;
}

.container {
text-align: center;
padding: 60px 20px;
min-height: 100vh;
display: flex;
flex-direction: column;
justify-content: center;
backdrop-filter: blur(4px);
}

.title {
font-size: 4rem;
font-weight: 900;
text-shadow: 0 0 30px #c084fc, 0 0 10px #ffffff;
margin-bottom: 10px;
letter-spacing: 2px;
}

.subtitle {
font-size: 1.3rem;
color: #ddd;
text-shadow: 0 0 12px #ffffff70;
margin-bottom: 50px;
}

.card {
background: rgba(255, 255, 255, 0.05);
border: 1px solid rgba(255, 255, 255, 0.1);
border-radius: 20px;
padding: 25px;
margin: 20px auto;
max-width: 500px;
text-decoration: none;
color: white;
box-shadow: 0 0 25px rgba(255, 255, 255, 0.05);
transition: transform 0.3s ease, box-shadow 0.3s ease;
backdrop-filter: blur(8px);
}

.card:hover {
transform: scale(1.045);
box-shadow: 0 0 40px rgba(168, 85, 247, 0.6);
}

.card h3 {
font-size: 1.6rem;
margin-bottom: 10px;
text-shadow: 0 0 12px white;
}

.card p {
color: #cccccc;
font-size: 0.95rem;
margin: 6px 0;
text-shadow: 0 0 5px #888;
}

.status {
color: #00ffc8;
font-weight: bold;
text-shadow: 0 0 6px #00ffcc;
}

.discord-button {
display: inline-block;
background-color: #8000ff;
padding: 15px 35px;
color: white;
font-weight: bold;
text-decoration: none;
border-radius: 14px;
box-shadow: 0 0 25px #a855f7;
transition: all 0.3s ease;
margin-top: 40px;
font-size: 1.1rem;
}

.discord-button:hover {
background-color: #a21caf;
box-shadow: 0 0 40px #f472b6;
transform: scale(1.05);
}

/* Pet Styles */
.pet-grid {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 30px;
margin-top: 50px;
}

.pet-card {
background: rgba(255, 255, 255, 0.05);
border-radius: 20px;
padding: 20px;
width: 200px;
text-align: center;
backdrop-filter: blur(6px);
box-shadow: 0 0 20px rgba(255, 255, 255, 0.07);
transition: transform 0.3s ease;
}

.pet-card:hover {
transform: scale(1.05);
}

.pet-card img {
width: 100%;
border-radius: 12px;
margin-bottom: 15px;
}

.pet-card h4 {
font-size: 1.2rem;
color: #fff;
margin: 10px 0 5px;
}

.pet-card p {
color: #a0f0ff;
font-weight: bold;
font-size: 1rem;
}
</style>
