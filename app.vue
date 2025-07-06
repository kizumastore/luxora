<template>
<div class="bg-wrap">
  <div class="container">
    <h1 class="title">𝐋𝐔𝐗𝐎𝐑𝐀</h1>
    <h2 class="subtitle">THE #1 SITE</h2>

    <!-- Generator -->
    <a
      href="https://app.genn.lu/auth/luxoraa"
      class="card"
      target="_blank"
      rel="noopener noreferrer"
    >
      <h3>🔗 Link Generator</h3>
      <p>🌐 Chrome: <span class="status">Unflagged</span></p>
      <p>🎵 TikTok: <span class="status">Unflagged</span></p>
    </a>

    <!-- Tutorial -->
    <a
      href="https://www.youtube.com/watch?v=xm-z0oneDUo"
      class="card"
      target="_blank"
      rel="noopener noreferrer"
    >
      <h3>📚 Tutorial</h3>
      <p>🛠️ Quick & clear how to use</p>
      <p>🎥 Short and concise video guide</p>
    </a>

    <!-- Discord -->
    <a
      href="https://discord.gg/BWYBef9FUM"
      class="discord-button"
      target="_blank"
      rel="noopener noreferrer"
    >
      💬 Join Our Discord Server
    </a>
  </div>
</div>
</template>

<style>
/* BACKGROUND ANIMATED */
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
</style>
